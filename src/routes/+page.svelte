<script >
  import TextInput from './TextInput.svelte';

  let value = $state('');
  const _snippet = snippet
</script>

{#snippet snippet()}
  Something
{/snippet}

<TextInput bind:value />
value:
{value}