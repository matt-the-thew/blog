<script lang="ts">
  import favicon from "#lib/assets/favicon.jpg";
  import Navbar from "#lib/+nav.svelte";
  import type { LayoutProps } from "./$types";
  import "#lib/fonts.css";

  let { children }: LayoutProps = $props();
</script>

<svelte:head>
  <link rel="icon" href={favicon} />
</svelte:head>

<Navbar />
<div class="page-wrap">
  {@render children()}
</div>

<style>
  :global(:root) {
    --font: "Tiny5";
    --primary: #f3f3f3;
    --accent: #1bb368;
  }

  .page-wrap {
    padding: 5rem 12rem;
  }
</style>
