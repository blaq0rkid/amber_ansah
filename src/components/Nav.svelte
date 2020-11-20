<script lang="ts">
	import {
	  Collapse,
	  Navbar,
	  NavbarToggler,
	  NavbarBrand,
	  Nav,
	  NavItem,
	  NavLink,
	  UncontrolledDropdown,
	  DropdownToggle,
	  DropdownMenu,
	  DropdownItem
	} from 'sveltestrap';
  
	let isOpen = false;
  
	function handleUpdate(event) {
	  isOpen = event.detail.isOpen;
	}
  </script>
  
  <style>
	  .icons {
		padding:0;
		list-style: none; 
		width:80%; 
		margin:0 auto;
	  }

	  li {		
		display: inline-block;
		text-align: center;
	  }
	  .icons li img {
		height: 50px;
		width: auto;
		float: left;
	  }
  </style>

<svelte:head>
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
</svelte:head>
  
<Navbar light expand="md fixed-top text-dark">
	<NavbarBrand href="/">Amber Ansah</NavbarBrand>	
<div class="icons">
	<li><img src="https://cdn2.iconfinder.com/data/icons/black-white-social-media/32/youtube_online_social_media_tube-128.png">
	</li>
	<li><img src="https://cdn1.iconfinder.com/data/icons/social-media-circle-7/512/Circled_Instagram_svg-128.png">
	</li>
	<li><img src="https://cdn2.iconfinder.com/data/icons/black-white-social-media/32/twitter_online_social_media-128.png">
	</li>
</div>

	<NavbarToggler on:click={() => (isOpen = !isOpen)} />
	<Collapse {isOpen} navbar expand="md" on:update={handleUpdate}>
	  <Nav class="ml-auto" navbar>
		<NavItem>
		  <NavLink href="videos">Videos</NavLink>
		</NavItem>
		<NavItem>
			<NavLink href="products">Products</NavLink>
		  </NavItem>
		<NavItem>
		  <NavLink href="tools">Tools</NavLink>
		</NavItem>
		<UncontrolledDropdown nav inNavbar>
		  <DropdownToggle nav caret>Fun</DropdownToggle>
		  <DropdownMenu right>
			<DropdownItem href="boss">Boss Babe</DropdownItem>
			<DropdownItem href="try">Try On Haul</DropdownItem>			
		  </DropdownMenu>
		</UncontrolledDropdown>
		<NavItem>
			<NavLink href="about">About</NavLink>
		</NavItem>
	  </Nav>
	</Collapse>
  </Navbar>