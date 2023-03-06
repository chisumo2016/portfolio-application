<template>
    <div class="bg-slate-200 dark:bg-slate-900">
        <!-- Header -->
        <Header></Header>
            <main class="min-h-screen">
                <slot/>
            </main>
        <!-- Footer -->
        <Footer></Footer>
    </div> <!--Parent Div-->
</template>

<script setup>

import Header from "@/Components/FrontEnd/Header.vue";
import Footer from "@/Components/FrontEnd/Footer.vue";
</script>

<style scoped>

</style>
