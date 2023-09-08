<script>
    /** @type {import('./$types').PageData} */
    export let data;
</script>

<h1>{data.title}</h1>
<div>{@html data.content}</div>
<p>U can also use +page.server.ts for private API keys and env</p>