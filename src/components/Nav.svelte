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
  

<svelte:head>
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
</svelte:head>
  
<Navbar color="light" light expand="md">
	<NavbarBrand href="/">Amber Ansah</NavbarBrand>
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
			<NavLink href="about">About Me</NavLink>
		</NavItem>
	  </Nav>
	</Collapse>
  </Navbar>