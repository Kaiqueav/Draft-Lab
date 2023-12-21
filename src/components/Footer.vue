<script setup>
    const props = defineProps(['logoFooter', 'github'])
</script>

 <template>
    <footer class="p-3 mt-2">
        <div class="flex flex-row justify- border-b-2 border-[#760EC8] pb-5  gap-7">
            <img :src="props.logoFooter">
            <p class="font-semibold ml-[100px] text-white">Newsletter</p>
         
        </div>
        <div class="flex flex-row mt-6">
            <img :src="props.github" alt="">
            <p class="text-white ml-2"> Criado por: </p>
            <span class="text-[#760EC8] ml-2"> eu</span>
        </div>
        
    </footer>
 </template>