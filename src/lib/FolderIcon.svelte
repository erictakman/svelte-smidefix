<script>
	export let size = 16;
	export let color = "#000";
</script>

<div style={"font-size: " + size + "px;"}>
	<svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path clip-rule="evenodd" d="M5 4L9.92963 4C10.9327 4 11.8694 4.5013 12.4258 5.3359L13.2383 6.5547C13.4238 6.8329 13.736 7 14.0704 7H19C20.6569 7 22 8.34315 22 10V18C22 19.6569 20.6569 21 19 21H5C3.34315 21 2 19.6569 2 18V7C2 5.34315 3.34315 4 5 4ZM9.92963 6H5C4.44772 6 4 6.44772 4 7V18C4 18.5523 4.44772 19 5 19H19C19.5523 19 20 18.5523 20 18V10C20 9.44772 19.5523 9 19 9H14.0704C13.0673 9 12.1306 8.4987 11.5742 7.6641L10.7617 6.4453C10.5762 6.1671 10.264 6 9.92963 6Z" fill={color} fill-rule="evenodd"></path>
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
