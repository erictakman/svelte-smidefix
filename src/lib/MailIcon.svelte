<script>
	export let size = 16;
	export let color = "#000";
</script>

<div style={"font-size: " + size + "px;"}>
	<svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path clip-rule="evenodd" d="M2 9.97694C1.99964 9.99245 1.99964 10.0079 2 10.0233V15C2 18.3137 4.68629 21 8 21H16C19.3137 21 22 18.3137 22 15V10.0233C22.0004 10.0079 22.0004 9.99245 22 9.97695V8C22 5.79086 20.2091 4 18 4H6C3.79086 4 2 5.79086 2 8V9.97694ZM6 6H18C19.1046 6 20 6.89543 20 8V9.27924L12.9487 11.6297C12.3329 11.8349 11.6671 11.8349 11.0513 11.6297L4 9.27924V8C4 6.89543 4.89543 6 6 6ZM20 11.3874V15C20 17.2091 18.2091 19 16 19H8C5.79086 19 4 17.2091 4 15V11.3874L10.4189 13.527C11.4452 13.8692 12.5548 13.8692 13.5811 13.527L20 11.3874Z" fill={color} fill-rule="evenodd"></path>
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
