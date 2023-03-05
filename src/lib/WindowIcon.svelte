<script>
	export let size = 16;
	export let color = "#000";
</script>

<div style={"font-size: " + size + "px;"}>
	<svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path d="M6 7C6.55228 7 7 6.55228 7 6C7 5.44772 6.55228 5 6 5C5.44772 5 5 5.44772 5 6C5 6.55228 5.44772 7 6 7Z" fill={color}></path>
		<path d="M10 6C10 6.55228 9.55228 7 9 7C8.44772 7 8 6.55228 8 6C8 5.44772 8.44772 5 9 5C9.55228 5 10 5.44772 10 6Z" fill={color}></path>
		<path d="M12 7C12.5523 7 13 6.55228 13 6C13 5.44772 12.5523 5 12 5C11.4477 5 11 5.44772 11 6C11 6.55228 11.4477 7 12 7Z" fill={color}></path>
		<path clip-rule="evenodd" d="M6 2C3.79086 2 2 3.79086 2 6V16C2 19.3137 4.68629 22 8 22H16C19.3137 22 22 19.3137 22 16V6C22 3.79086 20.2091 2 18 2H6ZM18 4H6C4.89543 4 4 4.89543 4 6V8H20V6C20 4.89543 19.1046 4 18 4ZM4 16V10H20V16C20 18.2091 18.2091 20 16 20H8C5.79086 20 4 18.2091 4 16Z" fill={color} fill-rule="evenodd"></path>
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
