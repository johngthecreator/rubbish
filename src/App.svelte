<script>
  import { Router, Link, Route } from "svelte-routing";
  import Home from "./routes/Home.svelte";
  import Upload from "./routes/Upload.svelte";
  import Locker from "./routes/Locker.svelte";
  import Nav from "./lib/Nav.svelte";
  export let url = "";
</script>
  <Router url={url}>
    <Nav />
    <div>
      <Route path="upload" component="{Upload}" />
      <Route path="locker" component="{Locker}" />
      <Route path="/"><Home /></Route>
    </div>
  </Router>