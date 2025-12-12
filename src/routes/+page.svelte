<script lang="ts">
	const message = await new Promise((resolve) =>
		setTimeout(() => resolve("Hello, World"), 1000),
	);
</script>

{message}
