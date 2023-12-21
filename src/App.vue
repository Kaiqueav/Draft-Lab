<script setup>

    import Header from './components/Header.vue'
    import Banner from './components/Banner.vue'
    import About from './components/About.vue'
    import Work from './components/Work.vue'
    import Faqs from './components/accordion/Faqs.vue'
    import Content from './components/accordion/Content.vue'
    import Footer from './components/Footer.vue'
    
</script>

<template>
    <header>
        <Header logo = "/img/Logo.png" />
        <Banner check = "/img/check-check.png" />
    </header>
    <div>
         <About heart = "/img/heart-handshake.png" world="/img/globe-2.png" smile="/img/smile-plus.png" users="/img/users.png"/>
         <Work />
         <Faqs  question=" Perguntas Frequentes" aria-title="incidents" title="Quem pode participar dos desafios da plataforma?">
            <Content></Content>
         </Faqs> 
         <Faqs  aria-title="incidents" title="É possível participar de mais de um desafio ao mesmo tempo?cking Incidents">
            <Content></Content>
         </Faqs> 
         <Faqs  aria-title="incidents" title="Quais são os incentivos para participar dos desafios?">
            <Content></Content>
         </Faqs> 
         <Faqs  aria-title="incidents" title="Posso participar mesmo não sendo um especialista em determinada área?">
            <Content></Content>
         </Faqs> 
         <Faqs  aria-title="incidents" title="Como posso encontrar membros para formar um time?">
            <Content></Content>
         </Faqs> 
    </div>
   <Footer logo-footer="/img/FooterLogo.png"  github="/img/github.png" />
   
</template>

<style scoped>
 
  
</style>
