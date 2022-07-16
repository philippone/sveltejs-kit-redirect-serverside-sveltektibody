<script context="module" lang="ts">
	export async function load({ fetch, url, stuff }) {

    return {
      status: 200,
      stuff: {
        data: 'foo'
      }
    }
  }

</script>


<script lang="ts">
import { onDestroy, onMount } from 'svelte';
	import { goto } from '$app/navigation';



onMount(() => {
  goto('./three');
})
</script>

<slot/>