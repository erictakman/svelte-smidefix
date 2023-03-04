<script>
	export let size = 16;
	export let color = "#000";
</script>

<div style={"font-size: " + size + "px;"}>
	<svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path d="M6 4H18C19.6569 4 21 5.34315 21 7V17C21 18.6569 19.6569 20 18 20H6C4.34315 20 3 18.6569 3 17V7C3 5.34315 4.34315 4 6 4Z" stroke="black" stroke-width="2"/>
<path d="M12 12H15" stroke="black" stroke-width="2" stroke-linecap="round"/>
<path d="M7 12L9 10L7 8" stroke="black" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
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
