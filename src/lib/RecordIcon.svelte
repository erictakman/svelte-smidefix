<script>
	export let size = 16;
	export let color = "#000";
</script>

<div style={"font-size: " + size + "px;"}>
	<svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path clip-rule="evenodd" d="M12 7C9.23858 7 7 9.23858 7 12C7 14.7614 9.23858 17 12 17C14.7614 17 17 14.7614 17 12C17 9.23858 14.7614 7 12 7ZM15 12C15 13.6569 13.6569 15 12 15C10.3431 15 9 13.6569 9 12C9 10.3431 10.3431 9 12 9C13.6569 9 15 10.3431 15 12Z" fill={color} fill-rule="evenodd"></path>
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
