<script>
    import Header from "./Header.svelte";
    import UseCaseInputList from "./UseCaseInputList.svelte";
    import UseCaseList from "./UseCaseList.svelte";
</script>

<Header />
<UseCaseInputList />
<UseCaseList />

<style global>
    /* purgecss start ignore */
    @tailwind base;
    @tailwind components;
    /* purgecss end ignore */
    @tailwind utilities;
</style>
