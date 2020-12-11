<script lang="ts">
  import {
    Button,
    Card,
    CardBody,
    CardHeader,
    CardSubtitle,
    CardText,
    CardTitle
  } from 'sveltestrap';
</script>

<style>
  section {
    padding-top: 6%;
  }
</style>

<section class="card-deck">
<Card>
  <CardHeader class="text-center">
    <CardTitle>Card title</CardTitle>
  </CardHeader>
  <CardBody>
    <CardSubtitle>Card subtitle</CardSubtitle>
    <CardText>
      Some quick example text to build on the card title and make up the bulk of
      the card's content.
    </CardText>
    <Button>Buy Now!</Button>
  </CardBody>
</Card>

<Card>
  <CardHeader class="text-center">
    <CardTitle>Card title</CardTitle>
  </CardHeader>
  <CardBody>
    <CardSubtitle>Card subtitle</CardSubtitle>
    <CardText>
      Some quick example text to build on the card title and make up the bulk of
      the card's content.
    </CardText>
    <Button>Buy Now!</Button>
  </CardBody>
</Card>

<Card>
  <CardHeader class="text-center">
    <CardTitle>Card title</CardTitle>
  </CardHeader>
  <CardBody>
    <CardSubtitle>Card subtitle</CardSubtitle>
    <CardText>
      Some quick example text to build on the card title and make up the bulk of
      the card's content.
    </CardText>
    <Button>Buy Now!</Button>
  </CardBody>
</Card>
</section>