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
img {
  height:auto;
  width: 10%;
}
</style>

<section class="card-deck">
<Card>
  <CardHeader class="text-center">
    <CardTitle>Shea Moisture</CardTitle>
  </CardHeader>
  <CardBody>
    <CardSubtitle class="text-center">Jamaican Black Castor Oil</CardSubtitle>
    <CardText >
      <!-- svelte-ignore a11y-missing-attribute -->
      <img src="https://images-na.ssl-images-amazon.com/images/I/71ckpYt9LxL._SL1500_.jpg">
    </CardText>
    <a href="https://www.amazon.com/stores/SheaMoisture/page/036A487E-7D7C-4DA2-BA08-052332E19E74?ref_=ast_bln"><Button>Buy Now!</Button></a>
  </CardBody>
</Card>

<Card>
  <CardHeader class="text-center">
    <CardTitle>Garnier</CardTitle>
  </CardHeader>
  <CardBody>
    <CardSubtitle class="text-center">Whole Blends</CardSubtitle>
    <CardText>
      <!-- svelte-ignore a11y-missing-attribute -->
      <img src="https://images-na.ssl-images-amazon.com/images/I/71XoM6MgXGL._SL1494_.jpg">
    </CardText>
    <a href="https://www.amazon.com/gp/item-dispatch/ref=dp_ebb_1?ie=UTF8&registryItemID.1=&submit.addToCart=addToCart&registryID.1=&offeringID.1=Dzl2CDItKCiWDOCsx5fQTSFaVSYMf9IFcWe4JXqHLIIbdL5uIP0VpxCbkYk2F1fEww3FHEU5avaYhgmUtuXVoocv9mooRF18RkIkztjvs2i2dcsExD6zfcod7kmOJpYFhLtrKGFBkk7V0hm2i8CZu2hQ%252Fpm7G44TQNo97kpOoJeLSn5d77j7aWb0TlUIs6z1&storeID=beauty&nodeID=&signInToHUC=0&session-id=147-4272438-3601028&itemCount=1"><Button>Buy Now!</Button></a>
  </CardBody>
</Card>

<Card>
  <CardHeader class="text-center">
    <CardTitle>Creme of Nature</CardTitle>
  </CardHeader>
  <CardBody>
    <CardSubtitle class="text-center">Maximum Hold Snot</CardSubtitle>
    <CardText>
      <!-- svelte-ignore a11y-missing-attribute -->
      <img src="https://images-na.ssl-images-amazon.com/images/I/71BPJ8WeEmL._SL1500_.jpg">
    </CardText>
    <a href="https://www.amazon.com/gp/offer-listing/B0718Y9GG6/ref=dp_olp_afts?ie=UTF8&condition=all"><Button>Buy Now!</Button></a>
  </CardBody>
</Card>
</section>