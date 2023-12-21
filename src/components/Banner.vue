<script setup>
    const props = defineProps (['check'])
</script>

<template>
     <div class="ml-4 ">
     <h1 class="text-white text-3xl font-bold ">Supere Desafios e <br>Desenvolva <br> Habilidades</h1>  
     </div>
     <div class=" flex flex-row items-center ml-4 mt-3">
         <img class="" :src="props.check">
          <p class="text-[#b6b2b2] ml-4">Desenvolva seu talento em equipe</p>
     </div>
     <div class=" flex flex-row items-center ml-4 mt-3">
         <img class="" :src="props.check">
          <p class="text-[#b6b2b2] ml-4">Mostre suas habilidades para o mundo</p>
     </div>
     <div class=" flex flex-row items-center ml-4 mt-3">
         <img class="" :src="props.check">
          <p class="text-[#b6b2b2] ml-4">Explore projetos criativos e <br> inovadores </p>
     </div>
     <div class="ml-4 mt-8 flex flex-row">
        <button class="text-white  bg-[#760EC8] hover:bg-[#8f0bf3a4] p-2 gap-4 rounded-[4px]">Explore Desafios</button>
        <button class="text-[#760EC8] hover:text-white ml-3"> Junte-se a Comunidade</button>
     </div>
    
</template>

<style scoped>

</style>