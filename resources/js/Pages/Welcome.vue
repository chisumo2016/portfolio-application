<template>
    <Head title="Welcome to Portfolio" />
    <FrontEndLayout>
    <!--    Hero Section primary-->
        <Hero></Hero>
    <!--    Promote Section tail-100 -->
        <Promote></Promote>
    <!--    About Section  secondary -->
    <!--    Skills Section  tail-100 -->
    <!--    Project Section  primary-->
    <!--    Service Section Secondary-->
    <!--    Contact Section primary-->

    </FrontEndLayout>
</template>

<script setup>
import { Head} from '@inertiajs/vue3';
import FrontEndLayout from "@/Layouts/FrontEnd.vue";
import Hero from "@/Components/FrontEnd/Hero.vue";
import Promote from "@/Components/FrontEnd/Promote.vue";

</script>

