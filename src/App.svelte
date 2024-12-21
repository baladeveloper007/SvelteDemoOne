<script>
   
    // @ts-ignore
    import { Router, Route } from '$app/navigation';
    // @ts-ignore
    import Home from './routes/home/+page.svelte';
    // @ts-ignore
    import Dashboard from './routes/dashboard/+page.svelte';
</script>

<Router>
    <Route path="/" component={Home} />
    <Route path="/dashboard" component={Dashboard} />
</Router>
