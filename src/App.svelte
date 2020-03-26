<script>
  import { Router } from 'svelte-router-spa'
  import { routes } from './routes'
</script>

<a href="/">Home</a>
<a href="login">Login</a>
<a href="admin">Admin</a>
<Router {routes} />