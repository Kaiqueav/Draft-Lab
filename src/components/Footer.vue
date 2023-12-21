<script setup>
    const props = defineProps(['logo-footer', 'github'])
</script>

 <template>
    <footer>
        <div>
            <img :src="logo-footer" >
        </div>
    </footer>
 </template>