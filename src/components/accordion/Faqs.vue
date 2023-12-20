<script setup>
    const items = [
        {
            id: 1,
            title: 'item 1',
            content: 'contudpdood'
        }
    ]
    const toggle = (item) =>{
        item.isOpen = !item.isOpen;
    };
</script>

<template>
    <div class="panel bg-black p-3">
        <h1 class="text-white mt-4 ml-4 text-2xl font-bold"> Perguntas Frequentes</h1>
        <div v-for="item in items" :key="item.id" class="text-white border-[3px] border-[#760EC8] p-2.5 mt-3.5 rounded-md">
            <figure @click="toggle(item)">{{ item.title }}</figure>
            <div :class="{'is-open': 'item.isOpen'}">
                {{ item.content }}
            </div>
        </div>
    </div>
</template>

<style scoped>

</style>