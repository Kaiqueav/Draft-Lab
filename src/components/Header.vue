<script setup>
     const props =  defineProps(['logo'])

    
</script>

<template>
     <nav class="p-5 flex flex-row items-center justify-between" >
        <img class="" :src="props.logo" alt="">
        <button class="text-white  bg-[#760EC8] hover:bg-[#8f0bf3a4] p-2 gap-4 rounded-[4px]">ACEITE O DESAFIO</button>
    </nav>
</template>


<style>

</style>