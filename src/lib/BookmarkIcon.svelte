<script>
	export let size = 16;
	export let color = "#000";
</script>

<div style={"font-size: " + size + "px;"}>
	<svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path d="M4 6C4 4.34315 5.34315 3 7 3H17C18.6569 3 20 4.34315 20 6V19.601C20 20.3635 19.1809 20.8454 18.5144 20.4751L13.4569 17.6654C12.5509 17.1621 11.4491 17.1621 10.5431 17.6654L5.48564 20.4751C4.81911 20.8454 4 20.3635 4 19.601V6Z" stroke="black" stroke-width="2"/>
	</svg>
</div>

<style>
	div {
		display: flex;
		margin: 0;
		padding: 0;
		width: max-content;
	}
	svg {
		width: 1em;
	}
</style>
