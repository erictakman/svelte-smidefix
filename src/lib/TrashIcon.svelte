<script>
	export let size = 16;
	export let color = "#000";
</script>

<div style={"font-size: " + size + "px;"}>
	<svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path d="M9 15C9 15.5523 9.44772 16 10 16C10.5523 16 11 15.5523 11 15V11C11 10.4477 10.5523 10 10 10C9.44772 10 9 10.4477 9 11V15Z" fill={color}></path>
		<path d="M14 16C13.4477 16 13 15.5523 13 15V11C13 10.4477 13.4477 10 14 10C14.5523 10 15 10.4477 15 11V15C15 15.5523 14.5523 16 14 16Z" fill={color}></path>
		<path clip-rule="evenodd" d="M8 5C8 3.34315 9.34315 2 11 2H13C14.6569 2 16 3.34315 16 5H20C20.5523 5 21 5.44772 21 6C21 6.55228 20.5523 7 20 7V18C20 20.2091 18.2091 22 16 22H8C5.79086 22 4 20.2091 4 18V7C3.44772 7 3 6.55228 3 6C3 5.44772 3.44772 5 4 5H8ZM10 5C10 4.44772 10.4477 4 11 4H13C13.5523 4 14 4.44772 14 5H10ZM6 7V18C6 19.1046 6.89543 20 8 20H16C17.1046 20 18 19.1046 18 18V7H6Z" fill={color} fill-rule="evenodd"></path>
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
