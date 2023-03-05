<script>
	export let size = 16;
	export let color = "#000";
</script>

<div style={"font-size: " + size + "px;"}>
	<svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path d="M12 3C10.8954 3 10 3.89543 10 5C10 6.10457 10.8954 7 12 7C13.1046 7 14 6.10457 14 5C14 3.89543 13.1046 3 12 3Z" fill={color}></path>
		<path d="M12 10C10.8954 10 10 10.8954 10 12C10 13.1046 10.8954 14 12 14C13.1046 14 14 13.1046 14 12C14 10.8954 13.1046 10 12 10Z" fill={color}></path>
		<path d="M10 19C10 17.8954 10.8954 17 12 17C13.1046 17 14 17.8954 14 19C14 20.1046 13.1046 21 12 21C10.8954 21 10 20.1046 10 19Z" fill={color}></path>
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
