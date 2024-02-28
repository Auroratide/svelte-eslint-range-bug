<!-- crash only happens when this is ts -->
<script lang="ts">
	import Component from "./Component.svelte"

	const num: number | undefined = 5
</script>

<Component num={num ?? 1} />
