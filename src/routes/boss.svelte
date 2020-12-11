<script lang="ts">
  import {      
    Card,
    CardBody,
    CardHeader,
    CardSubtitle,
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
    <CardTitle>Day In The Life</CardTitle>
  </CardHeader>
  <CardBody>
    <CardText class="embed-responsive embed-responsive-16by9">
      <iframe width="560" height="315" src="https://www.youtube.com/embed/_Rdsc9p-5RI" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </CardText>
  </CardBody>
</Card>
<Card class="col-sm-4">
  <CardHeader>
    <CardTitle>Mommy Q&A</CardTitle>
  </CardHeader>
  <CardBody>
    <CardText class="embed-responsive embed-responsive-16by9">
      <iframe width="560" height="315" src="https://www.youtube.com/embed/eFaHnCfXh5c" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </CardText>
  </CardBody>
</Card>
<Card class="col-sm-4">
  <CardHeader>
    <CardTitle>Mommy Q&A</CardTitle>
  </CardHeader>
  <CardBody>
    <CardText class="embed-responsive embed-responsive-16by9">
      <iframe width="560" height="315" src="https://www.youtube.com/embed/eFaHnCfXh5c" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </CardText>
  </CardBody>
</Card>
</Row>
</section>