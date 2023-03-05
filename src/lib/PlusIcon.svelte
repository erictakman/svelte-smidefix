<script>
	export let size = 16;
	export let color = "#000";
</script>

<div style={"font-size: " + size + "px;"}>
	<svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path d="M13 9C13 8.44772 12.5523 8 12 8C11.4477 8 11 8.44772 11 9V11H9C8.44772 11 8 11.4477 8 12C8 12.5523 8.44772 13 9 13H11V15C11 15.5523 11.4477 16 12 16C12.5523 16 13 15.5523 13 15V13H15C15.5523 13 16 12.5523 16 12C16 11.4477 15.5523 11 15 11H13V9Z" fill={color}></path>
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
