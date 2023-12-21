<script setup>

    import Header from './components/Header.vue'
    import Banner from './components/Banner.vue'
    import About from './components/About.vue'
    import Work from './components/Work.vue'
    import Faqs from './components/accordion/Faqs.vue'
    import Content from './components/accordion/Content.vue'
    
</script>

<template>
    <header>
        <Header logo = "/img/Header.Logo.png" />
        <Banner check = "/img/check-check.png" />
    </header>
    <div>
         
         <About heart = "/img/heart-handshake.png" world="/img/globe-2.png" smile="/img/smile-plus.png" users="/img/users.png"/>
         <Work />
         <Faqs  aria-title="incidents" title="Tracking Incidents">
            <Content> </Content>
         </Faqs> 
 
    </div>

</template>

<style scoped>
 
  
</style>
