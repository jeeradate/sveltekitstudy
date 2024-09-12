<script>
    import src from '$lib/assests/autohotkey.png';
    import Hello from '$lib/components/Hello.svelte';

</script>


<h1>Welcome to SvelteKit</h1>
<h1 class="myH1"><Hello /></h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<img src="{src}" alt=""  style="width: 300px;">

<style>
    .myH1 {
        color: blueviolet;
    } 
</style>