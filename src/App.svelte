<script>
	import { TextBox } from "fluent-svelte";

	let value = "Default value";
</script>

<TextBox bind:value />

<style>
    @import url("https://unpkg.com/fluent-svelte/theme.css");

    /* Some base styles to get things looking right. */
    :global(body) {
        background-color: var(--fds-solid-background-base);
        color: var(--fds-text-primary);
    }
</style>