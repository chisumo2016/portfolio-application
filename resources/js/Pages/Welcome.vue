<template>
    <Head title="Welcome to Portfolio" />
    <FrontEndLayout>
    <!--    Hero Section primary-->
        <Hero></Hero>
    <!--    Promote Section tail-100 -->
        <Promote></Promote>
    <!--    About Section  secondary -->
        <About></About>
    <!--    Skills Section  tail-100 -->
        <Skills :skills="skills"></Skills>
    <!--    Portfolio/Project Section  primary-->
        <Portifolio :skills="skills" :projects="projects"></Portifolio>
    <!--    Service Section Secondary-->
        <Services></Services>
    <!--    Contact Section primary-->
        <contact></contact>
    </FrontEndLayout>
</template>

<script setup>
import { Head} from '@inertiajs/vue3';
import FrontEndLayout from "@/Layouts/FrontEnd.vue";
import Hero from "@/Components/FrontEnd/Hero.vue";
import Promote from "@/Components/FrontEnd/Promote.vue";
import About from "@/Components/FrontEnd/About.vue";
import Skills from "@/Components/FrontEnd/Skills.vue";
import Portifolio from "@/Components/FrontEnd/Portifolio.vue";
import Services from "@/Components/FrontEnd/Services.vue";
import Contact from "@/Components/FrontEnd/Contact.vue";

defineProps({
    skills: Object,
    projects: Object
})
</script>

