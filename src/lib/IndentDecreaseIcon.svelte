<script>
	export let size = 16;
	export let color = "#000";
</script>

<div style={"font-size: " + size + "px;"}>
	<svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path d="M3 4C2.44772 4 2 4.44772 2 5C2 5.55228 2.44772 6 3 6H21C21.5523 6 22 5.55228 22 5C22 4.44772 21.5523 4 21 4H3Z" fill={color}></path>
		<path d="M9 9C8.44772 9 8 9.44772 8 10C8 10.5523 8.44772 11 9 11H21C21.5523 11 22 10.5523 22 10C22 9.44772 21.5523 9 21 9H9Z" fill={color}></path>
		<path d="M2 20C2 19.4477 2.44772 19 3 19H21C21.5523 19 22 19.4477 22 20C22 20.5523 21.5523 21 21 21H3C2.44772 21 2 20.5523 2 20Z" fill={color}></path>
		<path d="M9 14C8.44772 14 8 14.4477 8 15C8 15.5523 8.44772 16 9 16H21C21.5523 16 22 15.5523 22 15C22 14.4477 21.5523 14 21 14H9Z" fill={color}></path>
		<path d="M2.4 11.7L5.2 9.6C5.52962 9.35279 6 9.58798 6 10V15C6 15.412 5.52962 15.6472 5.2 15.4L2.4 13.3C2.14819 13.1111 2 12.8148 2 12.5C2 12.1852 2.14819 11.8889 2.4 11.7Z" fill={color}></path>
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
