<template>
    <div class="flex flex-row flex-wrap align-center justify-center text-center">
        <input type="text" placeholder="Enter Todo" class="px-3 py-3 placeholder-blueGray-300 text-blueGray-600 relative w-48 m-10 bg-white bg-white rounded text-sm border border-indigo-500 outline-none focus:outline-none focus:ring w-full"/>
        <button  class="bg-pink-500 text-white active:bg-emerald-600 font-bold uppercase text-sm px-6 py-3 rounded shadow hover:shadow-lg outline-none focus:outline-none mr-1 mb-1 ease-linear transition-all duration-150">Create</button>
    </div>
</template>

<script>
export default {
    name:'InputBox'
}
</script>