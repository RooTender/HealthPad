<script lang="ts">
  import Datatables from './lib/Datatables.svelte'
  import Navigation from './lib/Navigation.svelte';
  import { Container, Row, Col, Styles } from 'sveltestrap';
</script>

<Styles />

<Container>
  <Row>
    <Col>
      <Navigation />
    </Col>
  </Row>
  
  <Row>
    <Col>
      <Datatables/>
    </Col>
  </Row>
</Container>