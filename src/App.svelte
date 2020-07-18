<script>
    import {Router, Route, Link} from "svelte-routing"

    import Home from "./components/Home.svelte"
    import About from "./components/About.svelte"
</script>

<Router>
    <nav>
        <Link to="/">Home</Link>
        <Link to="/about">About</Link>
    </nav>

    <Route path="/">
        <Home />
    </Route>

    <Route path="/about">
        <About />
    </Route>
</Router>
