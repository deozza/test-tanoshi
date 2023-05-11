<script lang="ts">

    import TanoshiHeaderModel from 'tanoshi/src/lib/atoms/header/TanoshiHeaderModel';
    import TanoshiHeader from 'tanoshi/src/lib/atoms/header/TanoshiHeader.svelte';

    const testHeader: TanoshiHeaderModel = new TanoshiHeaderModel('Welcome to Sveltekit').setDisplaySize('6xl').setHtmlSize('h1')

</script>

<TanoshiHeader tanoshiHeaderModel={testHeader}/>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
