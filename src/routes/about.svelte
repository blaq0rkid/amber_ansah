<script lang="ts">
  import { Jumbotron } from 'sveltestrap';
  import { Card } from 'sveltestrap';
  </script>
  
  <style>
    section {
        padding-top: 6%;
        background-color: #FAFAFA; 
    }

    h5 {
      padding-top: 45%;
      padding-left: 25%;
      width: 85%;
      text-align: center;  
      color: black;    
    }

</style>
<section>
  <Jumbotron fluid class="p-3" >	
	<!-- svelte-ignore a11y-img-redundant-alt -->
	<img class="card-img" src="https://i.ytimg.com/vi/0feP32qea3U/maxresdefault.jpg" alt="Card image" style="opacity: .7">
		<div class="card-img-overlay"  >
      <h5 ><Card body color="transparent"  >Amber is a natural hair vlogger who has risen to fame for her self-titled YouTube channel's content. She has earned massive popularity by reviewing unique and innovative hair tools, in addition to journaling her natural hair journey.</Card></h5></div>
  </Jumbotron>
</section>