<script>
  export let title;
  export let description;
</script>

<h2>{title}</h2>
<slot />

<svelte:head>
  <title>{title} | KubeHuddle</title>
  <meta name="description" content={description} />
</svelte:head>
