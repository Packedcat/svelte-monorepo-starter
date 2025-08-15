<script lang="ts">
  import '../app.css'

  import { answer } from '@sv-mono/shared'

  import favicon from '$lib/assets/favicon.svg'

  let { children } = $props()
</script>

<svelte:head>
  <link rel="icon" href={favicon} />
</svelte:head>

{@render children?.()}
<div>{answer}</div>
