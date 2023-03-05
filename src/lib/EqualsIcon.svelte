<script>
	export let size = 16;
	export let color = "#000";
</script>

<div style={"font-size: " + size + "px;"}>
	<svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path d="M9 13C8.44772 13 8 13.4477 8 14C8 14.5523 8.44772 15 9 15H15C15.5523 15 16 14.5523 16 14C16 13.4477 15.5523 13 15 13H9Z" fill={color}></path>
		<path d="M9 9C8.44771 9 8 9.44772 8 10C8 10.5523 8.44772 11 9 11H15C15.5523 11 16 10.5523 16 10C16 9.44771 15.5523 9 15 9L9 9Z" fill={color}></path>
		<path clip-rule="evenodd" d="M2 10C2 5.58172 5.58172 2 10 2H14C18.4183 2 22 5.58172 22 10V14C22 18.4183 18.4183 22 14 22H10C5.58172 22 2 18.4183 2 14V10ZM10 4H14C17.3137 4 20 6.68629 20 10V14C20 17.3137 17.3137 20 14 20H10C6.68629 20 4 17.3137 4 14V10C4 6.68629 6.68629 4 10 4Z" fill={color} fill-rule="evenodd"></path>
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
