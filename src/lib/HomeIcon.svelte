<script>
	export let size = 16;
	export let color = "#000";
</script>

<div style={"font-size: " + size + "px;"}>
	<svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path d="M12 13C11.4477 13 11 13.4477 11 14C11 14.5523 11.4477 15 12 15C12.5523 15 13 14.5523 13 14C13 13.4477 12.5523 13 12 13Z" fill={color}></path>
		<path clip-rule="evenodd" d="M3 10.9014C3 9.53074 3.70182 8.25551 4.85979 7.52213L9.85979 4.35546C11.1666 3.52783 12.8334 3.52783 14.1402 4.35546L19.1402 7.52213C20.2982 8.25551 21 9.53074 21 10.9014V20C21 21.1046 20.1046 22 19 22H5C3.89543 22 3 21.1046 3 20V10.9014ZM19 10.9014V20L5 20L5 10.9014C5 10.2161 5.35091 9.57846 5.9299 9.21177L10.9299 6.0451C11.5833 5.63129 12.4167 5.63129 13.0701 6.0451L18.0701 9.21177C18.6491 9.57846 19 10.2161 19 10.9014Z" fill={color} fill-rule="evenodd"></path>
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
