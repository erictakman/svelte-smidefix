<script>
	export let size = 16;
	export let color = "#000";
</script>

<div style={"font-size: " + size + "px;"}>
	<svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path d="M8 13C8 12.4477 8.44772 12 9 12H15C15.5523 12 16 12.4477 16 13C16 13.5523 15.5523 14 15 14H9C8.44772 14 8 13.5523 8 13Z" fill={color}></path>
		<path d="M9 16C8.44772 16 8 16.4477 8 17C8 17.5523 8.44772 18 9 18H12C12.5523 18 13 17.5523 13 17C13 16.4477 12.5523 16 12 16H9Z" fill={color}></path>
		<path clip-rule="evenodd" d="M21 18C21 20.2091 19.2091 22 17 22H7C4.79086 22 3 20.2091 3 18V6C3 3.79086 4.79086 2 7 2H14.1716C14.702 2 15.2107 2.21071 15.5858 2.58579L20.4142 7.41421C20.7893 7.78929 21 8.29799 21 8.82843V18ZM19 18C19 19.1046 18.1046 20 17 20H7C5.89543 20 5 19.1046 5 18V6C5 4.89543 5.89543 4 7 4H13V7C13 8.65685 14.3431 10 16 10H19V18ZM18.1716 8H16C15.4477 8 15 7.55228 15 7V4.82843L18.1716 8Z" fill={color} fill-rule="evenodd"></path>
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
