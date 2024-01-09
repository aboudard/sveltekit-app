<script>
let veggie = 'Fenouil';
console.log(veggie);
</script>

<h1>Welcome to SvelteKit</h1>
<input bind:value={veggie} />
<p>Veggie : {veggie}</p>