<script>
  import { Router, Route } from "svero";
  import Navbar from "./components/Navbar.svelte";
  import Index from "./pages/index.svelte";
  import Products from "./pages/products.svelte";
</script>

<Navbar />

<div class="container">
  <Router>
    <Route path="*" component={Index} />
    <Route path="/products" component={Products} />
  </Router>
</div>
