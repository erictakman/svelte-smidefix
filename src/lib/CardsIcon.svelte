<script>
	export let size = 16;
	export let color = "#000";
</script>

<div style={"font-size: " + size + "px;"}>
	<svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
		<path clip-rule="evenodd" d="M2 6C2 3.79086 3.79086 2 6 2H7C9.20914 2 11 3.79086 11 6V7C11 9.20914 9.20914 11 7 11H6C3.79086 11 2 9.20914 2 7V6ZM6 4H7C8.10457 4 9 4.89543 9 6V7C9 8.10457 8.10457 9 7 9H6C4.89543 9 4 8.10457 4 7V6C4 4.89543 4.89543 4 6 4Z" fill={color} fill-rule="evenodd"></path>
		<path clip-rule="evenodd" d="M13 6C13 3.79086 14.7909 2 17 2H18C20.2091 2 22 3.79086 22 6V7C22 9.20914 20.2091 11 18 11H17C14.7909 11 13 9.20914 13 7V6ZM17 4H18C19.1046 4 20 4.89543 20 6V7C20 8.10457 19.1046 9 18 9H17C15.8954 9 15 8.10457 15 7V6C15 4.89543 15.8954 4 17 4Z" fill={color} fill-rule="evenodd"></path>
		<path clip-rule="evenodd" d="M6 13C3.79086 13 2 14.7909 2 17V18C2 20.2091 3.79086 22 6 22H7C9.20914 22 11 20.2091 11 18V17C11 14.7909 9.20914 13 7 13H6ZM7 15H6C4.89543 15 4 15.8954 4 17V18C4 19.1046 4.89543 20 6 20H7C8.10457 20 9 19.1046 9 18V17C9 15.8954 8.10457 15 7 15Z" fill={color} fill-rule="evenodd"></path>
		<path clip-rule="evenodd" d="M13 17C13 14.7909 14.7909 13 17 13H18C20.2091 13 22 14.7909 22 17V18C22 20.2091 20.2091 22 18 22H17C14.7909 22 13 20.2091 13 18V17ZM17 15H18C19.1046 15 20 15.8954 20 17V18C20 19.1046 19.1046 20 18 20H17C15.8954 20 15 19.1046 15 18V17C15 15.8954 15.8954 15 17 15Z" fill={color} fill-rule="evenodd"></path>
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
