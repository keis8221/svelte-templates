<script lang="ts">
  import TailwindCSS from "./TailwindCSS.svelte";
  import { Router } from "@roxi/routify";
  import { routes } from "./../.routify/routes";
</script>

<TailwindCSS />
<Router {routes} />
