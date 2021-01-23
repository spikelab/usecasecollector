<script>
    import Header from "./Header.svelte";
    import UseCaseInput from "./UseCaseInput.svelte";
    import UseCaseList from "./UseCaseList.svelte";
</script>

<Header />
<UseCaseInput />
<UseCaseList />

<style global>
    /* purgecss start ignore */
    @tailwind base;
    @tailwind components;
    /* purgecss end ignore */
    @tailwind utilities;
</style>
