<script>
	export let size = 16;
	export let color = "#000";
</script>

<div style={"font-size: " + size + "px;"}>
	<svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path d="M3 3C2.44772 3 2 3.44772 2 4V6C2 6.55228 2.44772 7 3 7H5C5.55228 7 6 6.55228 6 6V4C6 3.44772 5.55228 3 5 3H3Z" fill={color}></path>
		<path d="M9 5C9 4.44772 9.44772 4 10 4H21C21.5523 4 22 4.44772 22 5C22 5.55228 21.5523 6 21 6H10C9.44772 6 9 5.55228 9 5Z" fill={color}></path>
		<path d="M9 12C9 11.4477 9.44772 11 10 11H21C21.5523 11 22 11.4477 22 12C22 12.5523 21.5523 13 21 13H10C9.44772 13 9 12.5523 9 12Z" fill={color}></path>
		<path d="M10 18C9.44772 18 9 18.4477 9 19C9 19.5523 9.44772 20 10 20H21C21.5523 20 22 19.5523 22 19C22 18.4477 21.5523 18 21 18H10Z" fill={color}></path>
		<path d="M2 11C2 10.4477 2.44772 10 3 10H5C5.55228 10 6 10.4477 6 11V13C6 13.5523 5.55228 14 5 14H3C2.44772 14 2 13.5523 2 13V11Z" fill={color}></path>
		<path d="M3 17C2.44772 17 2 17.4477 2 18V20C2 20.5523 2.44772 21 3 21H5C5.55228 21 6 20.5523 6 20V18C6 17.4477 5.55228 17 5 17H3Z" fill={color}></path>
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
