<script lang="ts">
    import { Card, Row, Col } from 'sveltestrap';
</script>

<style>
    section {
        padding-top: 6%;
    }

</style>

<section>
    <Row>
        <Col xs="7">
            <Card class="text-white">
            <!-- svelte-ignore a11y-img-redundant-alt -->
            <img class="card-img" src="https://www.naturalhairmag.com/wp-content/uploads/2018/06/amber.ansah-.jpg" alt="Card image">
            <div class="card-img-overlay">
            <h5 class="card-title">Card title</h5>
                <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                <p class="card-text">Last updated 3 mins ago</p>
        </Card>
    </Col>
    
            <Col xs="5">
            <div class="card border-dark mb-3" >
                <div class="card-body text-dark">
                    <h5 class="card-title">Dark card title</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                </div>
            </div>        
    </Col>
    </Row>
</section>