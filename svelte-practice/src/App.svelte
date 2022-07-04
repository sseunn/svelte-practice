<script>
 let name = 'world';
 let age = 85
 function assign {
	 name = 'Heropy'
	 age = 36
 }
</script>

<main>
	<h1>Hello {name}!</h1> 
	<h2 class ={age <85? 'active': ''}>{age}</h2>
	<img src = "" alt ={name}/>
	<input type = text value = {name} />
	<button on:click={assign}>assign</button>
</main>

<style>
	h1 {
		color: red; 
	}
	.active {
		color:blue;
	}
</style>