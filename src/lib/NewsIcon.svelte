<script>
	export let size = 16;
	export let color = "#000";
</script>

<div style={"font-size: " + size + "px;"}>
	<svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path clip-rule="evenodd" d="M9 8C9 6.34315 10.3431 5 12 5H14C15.6569 5 17 6.34315 17 8V9C17 10.6569 15.6569 12 14 12H12C10.3431 12 9 10.6569 9 9V8ZM12 7H14C14.5523 7 15 7.44772 15 8V9C15 9.55228 14.5523 10 14 10H12C11.4477 10 11 9.55228 11 9V8C11 7.44772 11.4477 7 12 7Z" fill={color} fill-rule="evenodd"></path>
		<path d="M9 14C9 13.4477 9.44772 13 10 13H13C13.5523 13 14 13.4477 14 14C14 14.5523 13.5523 15 13 15H10C9.44772 15 9 14.5523 9 14Z" fill={color}></path>
		<path d="M10 16C9.44772 16 9 16.4477 9 17C9 17.5523 9.44772 18 10 18H16C16.5523 18 17 17.5523 17 17C17 16.4477 16.5523 16 16 16H10Z" fill={color}></path>
		<path clip-rule="evenodd" d="M6 5C6 3.34315 7.34315 2 9 2H17C18.6569 2 20 3.34315 20 5V19C20 20.6569 18.6569 22 17 22H5C3.34315 22 2 20.6569 2 19V11C2 9.34315 3.34315 8 5 8H6V5ZM17 20H7.82929C7.93985 19.6872 8 19.3506 8 19V5C8 4.44772 8.44772 4 9 4H17C17.5523 4 18 4.44772 18 5V19C18 19.5523 17.5523 20 17 20ZM6 19V10H5C4.44772 10 4 10.4477 4 11V19C4 19.5523 4.44772 20 5 20C5.55228 20 6 19.5523 6 19Z" fill={color} fill-rule="evenodd"></path>
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
