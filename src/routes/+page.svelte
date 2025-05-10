<script>
  import { Alert } from "flowbite-svelte";
  import { InfoCircleSolid } from "flowbite-svelte-icons";
</script>


<div class="p-8 max-w-4xl mx-auto">
<h1 class="text-3xl">
  Flowbite-Svelte GitHub Issue Template
</h1>

<Alert>
  {#snippet icon()}<InfoCircleSolid class="h-5 w-5" />{/snippet}
  <span class="font-medium">Testing alert</span>
  Lorem ipsum dolor sit amet consectetur.
</Alert>
<p>Run pnpm update and then add your code here</p>
</div>