<script>
    	let bgColor = 'primary'
</script>

<div class="box">
        <label for="bg-color-box">{bgColor}</label>
        <input id="bg-color-box" type="color" bind:value={bgColor} />
</div>

<style>
	.box {
		border: 1px solid #aaa;
		padding: 1em;
		margin: 20px;
	}
</style>