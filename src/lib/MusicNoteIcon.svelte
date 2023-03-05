<script>
	export let size = 16;
	export let color = "#000";
</script>

<div style={"font-size: " + size + "px;"}>
	<svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path d="M13.4607 7.39253C14.7361 7.03545 16 7.9941 16 9.31846V15C16 16.1046 15.1046 17 14 17C12.8954 17 12 16.1046 12 15C12 13.8954 12.8954 13 14 13L14 9.31846L11 10.1585V15C11 16.1046 10.1046 17 9 17C7.89543 17 7 16.1046 7 15C7 13.8954 7.89543 13 9 13V9.77923C9 9.10656 9.44781 8.51615 10.0956 8.33478L13.4607 7.39253Z" fill={color}></path>
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
