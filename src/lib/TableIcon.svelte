<script>
	export let size = 16;
	export let color = "#000";
</script>

<div style={"font-size: " + size + "px;"}>
	<svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path clip-rule="evenodd" d="M3 20C3 20.5523 3.44772 21 4 21H20C20.5523 21 21 20.5523 21 20V5C21 4.44772 20.5523 4 20 4H4C3.44772 4 3 4.44772 3 5V20ZM5 9V6H11V9H5ZM13 14V11H19V14H13ZM11 19V16H5V19H11ZM5 14V11H11V14H5ZM13 16V19H19V16H13ZM13 6V9H19V6H13Z" fill={color} fill-rule="evenodd"></path>
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
