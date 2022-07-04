<script>
	let name='world'
	let toggle = false
	if (toffle){
	 	//JavaScript 조건문 
	}
</script>

<main>
<button on:click={() => (toggle=!toggle)}> toggle </button>
{#if toggle}
<h1>Hello! {name}! </h1>
{/if}  
</main>

<style>
	h1 {
		color: red; 
	}
	.active {
		color:blue;
	}
</style>