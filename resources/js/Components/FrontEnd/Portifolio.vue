<template>
 <section id="portfolio" class="section bg-light-primary dark:bg-dark-primary min-h-[1400px]">
     <div class="container mx-auto"
      v-motion
      :initial="{
              opacity: 0,
              y: 100,
            }"
      :visible="{
              opacity: 1,
              y: 0,
       }"
     >
         <div class="flex flex-col items-center text-center">
             <h2 class="section-title">My Latest Work</h2>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. A accusantium amet, atque, aut commodi delectus ducimus explicabo fuga fugit illo obcaecati, odit reiciendis repellendus reprehenderit rerum soluta ullam. Dolore, sed?
         </div>
     </div>
     <Projects :skills="skills" :projects="projects"></Projects>
 </section>
</template>

<script setup>
import Projects from "@/Components/FrontEnd/Projects.vue";

defineProps({
    projects: Object,
    skills : Object
})
</script>

<style scoped>

</style>
