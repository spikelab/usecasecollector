<script>
    import Header from "./Header.svelte";
    import UseCaseInput from "./UseCaseInput.svelte";
    import UseCaseList from "./UseCaseList.svelte";
</script>

<Header />
<UseCaseInput />
<UseCaseList />
<svg class="w-6 h-6"
    xmlns="http://www.w3.org/2000/svg"
    viewBox="0 0 16 16"
    fill="currentColor"
    color="#000000">
    <path
        fill-rule="evenodd"
        d="M13.03 8.22a.75.75 0 010 1.06l-4.25 4.25a.75.75 0 01-1.06 0L3.47 9.28a.75.75 0 011.06-1.06l2.97 2.97V3.75a.75.75 0 011.5 0v7.44l2.97-2.97a.75.75 0 011.06 0z"
    />
</svg>

<style global>
    /* purgecss start ignore */
    @import "tailwindcss/base";
    @import "tailwindcss/components";
    /* purgecss end ignore */
    @import "tailwindcss/utilities";
</style>
