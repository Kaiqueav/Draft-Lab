<!-- componente da pagina com corações -->

<script setup>
     const props = defineProps(['heart', 'world', 'smile', 'users'])

</script>

<template>
    <div class="bg-black mt-4 ">
            <div class="p-2.5 ">
                <figure class="flex flex-around flex-row ">
                    <img class="w-6 ml-1.5" :src="props.heart" alt="">
                    <span class="text-white ml-4"> Trabalhe em equipe</span> 
                </figure>
                <div>
                     <p class="text-white mt-[6px] ml-4 p-2 border-l-4 border-[#760EC8]">Na força da colaboração e cooperação,<br>
                         encontramos o caminho para o sucesso <br> 
                         trabalhando em equipe, superando <br>
                         desafios e alcançando grandes <br> conquistas
                        </p>
                </div>
            </div>
                    <!-- div mostre suas habilidades -->
            <div class="p-2.5 ">
                <figure class="flex flex-around flex-row ">
                    <img class="w-6 ml-1.5" :src="props.world" alt="">
                    <span class="text-white ml-4">Mostre suas habilidades</span> 
                </figure>
                <div>
                     <p class="text-white mt-[6px] ml-4 p-2 border-l-4 border-[#760EC8]">Na força da colaboração e cooperação,<br>
                         Brilhe ao demonstrar suas habilidades<br>
                         em ação! Supere desafios, colabore <br>
                         coletivamente e alcance resultados excepcionais, mostrando ao mundo <br>
                         o poder da cooperação
                        </p>
                </div>
            </div>
            <!-- criatividade em ação -->
            <div class="p-2.5 ">
                <figure class="flex flex-around flex-row ">
                    <img class="w-6 ml-1.5" :src="props.smile" alt="">
                    <span class="text-white ml-4">Criatividade em ação</span> 
                </figure>
                <div>
                     <p class="text-white mt-[6px] ml-4 p-2 border-l-4 border-[#760EC8]">Na força da colaboração e cooperação,<br>
                        Desperte sua imaginação e supere <br>
                        limites!, exploraremos a magia da <br>
                        criatividade em ação. Traga sua visão <br>
                        única e trabalhe em equipe para <br>
                        transformar ideias em soluções incríveis
                     </p>
                </div>
            </div>

            <!-- Expanda suas conexões -->

            <div class="p-2.5 ">
                <figure class="flex flex-around flex-row ">
                    <img class="w-6 ml-1.5" :src="props.users" alt="">
                    <span class="text-white ml-4">Expanda suas conexões</span> 
                </figure>
                <div>
                     <p class="text-white mt-[6px] ml-4 p-2 border-l-4 border-[#760EC8]">Na força da colaboração e cooperação,<br>
                        Desperte sua imaginação e supere <br>
                        limites!, exploraremos a magia da <br>
                        criatividade em ação. Traga sua visão <br>
                        única e trabalhe em equipe para <br>
                        transformar ideias em soluções incríveis
                     </p>
                </div>
            </div>
            <button class="text-[#760EC8] ml-3.5 mt-3.5 mb-7"> Saiba mais</button>
    </div>

</template>

<style scoped>

</style>