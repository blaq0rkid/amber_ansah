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
    }
</style>
<section>
    <Row>
<Card class="col-sm-4">
  <CardHeader>
    <CardTitle>Video title</CardTitle>
  </CardHeader>
  <CardBody>
    <CardText class="embed-responsive embed-responsive-16by9">
      <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/zpOULjyy-n8?rel=0" allowfullscreen></iframe>
    </CardText>
  </CardBody>
</Card>
<Card class="col-sm-4">
  <CardHeader>
    <CardTitle>Video title</CardTitle>
  </CardHeader>
  <CardBody>
    <CardText class="embed-responsive embed-responsive-16by9">
      <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/zpOULjyy-n8?rel=0" allowfullscreen></iframe>
    </CardText>
  </CardBody>
</Card>
<Card class="col-sm-4">
  <CardHeader>
    <CardTitle>Video title</CardTitle>
  </CardHeader>
  <CardBody>
    <CardText class="embed-responsive embed-responsive-16by9">
      <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/zpOULjyy-n8?rel=0" allowfullscreen></iframe>
    </CardText>
  </CardBody>
</Card>
</Row>
</section>