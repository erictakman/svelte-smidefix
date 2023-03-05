<script>
	export let size = 16;
	export let color = "#000";
</script>

<div style={"font-size: " + size + "px;"}>
	<svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path d="M8 8C8 7.44772 8.44772 7 9 7C9.55228 7 10 7.44772 10 8C10 8.55228 9.55228 9 9 9C8.44772 9 8 8.55228 8 8Z" fill={color}></path>
		<path d="M11.5 12.866C11.2239 12.3877 11.3877 11.7761 11.866 11.5L17.0622 8.5C17.5405 8.22386 18.1521 8.38773 18.4282 8.86603C18.7043 9.34432 18.5405 9.95591 18.0622 10.2321L12.866 13.2321C12.3877 13.5082 11.7761 13.3443 11.5 12.866Z" fill={color}></path>
		<path clip-rule="evenodd" d="M10 2C5.58172 2 2 5.58172 2 10V14C2 18.4183 5.58172 22 10 22H14C18.4183 22 22 18.4183 22 14V10C22 5.58172 18.4183 2 14 2H10ZM14 4H10C6.68629 4 4 6.68629 4 10V14C4 17.3137 6.68629 20 10 20H14C17.3137 20 20 17.3137 20 14V10C20 6.68629 17.3137 4 14 4Z" fill={color} fill-rule="evenodd"></path>
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
