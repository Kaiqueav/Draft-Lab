<script setup>
import { ref } from 'vue';
const props = defineProps({
    title: { type: String, required: true },
    ariaTitle: { type: String, required: true }
});
const showPanel = ref(false);
const togglePanel = (event) => {
    showPanel.value = !showPanel.value;
}
</script>

<template>
    <div class="bg-black p-2">
      <h1 class="text-white ml-4 mt-4 text-lg font-bold ">  Perguntas Frequentes </h1>
        <div class="panel container mb-4 mt-4 border-2 border-[#760EC866]  active:border-[#760EC8] rounded-lg   text-white">
            <button :arial-controls="'accordion-content-' + ariaTitle" :id="'accordion-control-' + ariaTitle"
                @click.prevent="togglePanel"
                class="p-4 w-full font-semibold flex flex-row items-center justify-between">
                {{ title }}
                <span class="material-icons" v-if="showPanel">
                    expand_more
                </span>
                <span class="material-icons" v-else>
                    chevron_right
                </span>
            </button>
            <div :aria-hidden="!showPanel" :id="'content-' + ariaTitle" class="p-4" v-if="showPanel">
                <slot></slot>
            </div>
        </div>
    </div>
</template>

<style scoped></style>