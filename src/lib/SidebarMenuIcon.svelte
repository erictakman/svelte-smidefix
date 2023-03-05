<script>
	export let size = 16;
	export let color = "#000";
</script>

<div style={"font-size: " + size + "px;"}>
	<svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path d="M3 4C2.44772 4 2 4.44772 2 5C2 5.55228 2.44772 6 3 6H21C21.5523 6 22 5.55228 22 5C22 4.44772 21.5523 4 21 4H3Z" fill={color}></path>
		<path d="M3 11C2.44772 11 2 11.4477 2 12C2 12.5523 2.44772 13 3 13H16C16.5523 13 17 12.5523 17 12C17 11.4477 16.5523 11 16 11H3Z" fill={color}></path>
		<path d="M2 19C2 18.4477 2.44772 18 3 18H11C11.5523 18 12 18.4477 12 19C12 19.5523 11.5523 20 11 20H3C2.44772 20 2 19.5523 2 19Z" fill={color}></path>
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
