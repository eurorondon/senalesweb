<script>
	import Latino from "./Latino.svelte";
	import { Router, Route, Link, link } from "Svelte-routing";
	import Home from "./Home.svelte";
</script>

<Router>
	<div>
		<Route path="/" component={Home} />
		<Route path="/latino" component={Latino} />
	</div>
</Router>
