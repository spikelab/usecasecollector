<script>
    import Button from "./Button.svelte";
</script>

<main class="m-4">
    <div class="mb-4">
        <div class="flex justify-between mb-4"><p>As</p><input type="text" value="" class=" focus:bg-red-100 outline-none ml-2 flex-auto border-dotted border-b-2 border-gray-400"></div>
        <div class="flex justify-between mb-4"><p>I want to use</p><input type="text" value="" class="focus:bg-red-100 outline-none ml-2 flex-auto border-dotted border-b-2 border-gray-400"></div>
        <div class="flex justify-between mb-4"><p>To</p><input type="text" value="" class="focus:bg-red-100 outline-none ml-2 flex-auto border-dotted border-b-2 border-gray-400"></div>
        <div class="flex justify-between mb-4"><p>So that</p><input type="text" value="" class="focus:bg-red-100 outline-none ml-2 flex-auto border-dotted border-b-2 border-gray-400"></div>
    </div>
    <Button />
</main>

<style>
</style>
