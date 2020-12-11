<script lang="ts">
  import {      
    Card,
    CardBody,
    CardHeader,
    CardText,
    CardTitle,
    Row
  } from 'sveltestrap';
</script>

<style>
    section {
        padding-top: 5%;
        text-align: center;
    }
</style>
<section>
    <Row>
<Card class="col-sm-4">
  <CardHeader>
    <CardTitle>Fashion Nova</CardTitle>
  </CardHeader>
  <CardBody>
    <CardText class="embed-responsive embed-responsive-16by9">
      <iframe width="560" height="315" src="https://www.youtube.com/embed/Fritd6BlOjo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </CardText>
  </CardBody>
</Card>
<Card class="col-sm-4">
  <CardHeader>
    <CardTitle>Curvy African Haul</CardTitle>
  </CardHeader>
  <CardBody>
    <CardText class="embed-responsive embed-responsive-16by9">
      <iframe width="560" height="315" src="https://www.youtube.com/embed/kh0Iyztn1ds" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </CardText>
  </CardBody>
</Card>
<Card class="col-sm-4">
  <CardHeader>
    <CardTitle>Thick Curvy Try On Haul</CardTitle>
  </CardHeader>
  <CardBody>
    <CardText class="embed-responsive embed-responsive-16by9">
      <iframe width="560" height="315" src="https://www.youtube.com/embed/9iSiNlzAeOs" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </CardText>
  </CardBody>
</Card>
</Row>
</section>