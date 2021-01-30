<script>
    export let label;
    export let ph;
    
    let hideMenu = true;
    function toggleMenu() {
        hideMenu = !hideMenu;
    }
</script>

<div class="flex justify-between mb-4">
    <label for={label.toLowerCase()}>{label}</label>
    <div class="flex-auto relative">
        <input
            id="{label.toLowerCase()}"
            type="text"
            placeholder="{ph}"
            on:focus={toggleMenu}
            on:blur={toggleMenu}
            class=" focus:bg-red-100 outline-none ml-2 px-2 border-dotted border-b-2 border-gray-400 w-full"
        />
        <div class:hidden={hideMenu} class="absolute z-50 bg-white border-2 border-t-0 border-gray-200 w-full ml-2 mt-1 rounded-b-lg max-h-24 overflow-hidden overflow-y-scroll shadow-md">
            <ul class="py-2 w-full">
                <li class="hover:bg-red-100 px-2 cursor-pointer">first value</li>
                <li class="hover:bg-red-100 px-2 cursor-pointer">second value</li>
                <li class="hover:bg-red-100 px-2 cursor-pointer">third value</li>
                <li class="hover:bg-red-100 px-2 cursor-pointer">fourth value</li>
                <li class="hover:bg-red-100 px-2 cursor-pointer">fifth value</li>
                <li class="hover:bg-red-100 px-2 cursor-pointer">sixth value</li>
            </ul>
        </div>
    </div>
</div>

<style>
</style>
