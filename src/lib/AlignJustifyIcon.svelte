<script>
	export let size = 16;
	export let color = "#000";
</script>

<div style={"font-size: " + size + "px;"}>
	<svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path d="M2 5C2 4.44772 2.44772 4 3 4H21C21.5523 4 22 4.44772 22 5C22 5.55228 21.5523 6 21 6H3C2.44772 6 2 5.55228 2 5Z" fill={color}></path>
		<path d="M2 10C2 9.44772 2.44772 9 3 9H21C21.5523 9 22 9.44772 22 10C22 10.5523 21.5523 11 21 11H3C2.44772 11 2 10.5523 2 10Z" fill={color}></path>
		<path d="M3 19C2.44772 19 2 19.4477 2 20C2 20.5523 2.44772 21 3 21H21C21.5523 21 22 20.5523 22 20C22 19.4477 21.5523 19 21 19H3Z" fill={color}></path>
		<path d="M2 15C2 14.4477 2.44772 14 3 14H21C21.5523 14 22 14.4477 22 15C22 15.5523 21.5523 16 21 16H3C2.44772 16 2 15.5523 2 15Z" fill={color}></path>
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
