<template>
    <div class="main">
        <foods></foods>
        <foodrink></foodrink>
        <coffacke></coffacke>
        <recommend></recommend>
        <footers></footers>
        <navigation></navigation>
    </div>
  </template>
  
  <script>
  import foods from "@/components/foods.vue"
  import foodrink from "@/components/foodrink.vue"
  import coffacke from "@/components/coffacke.vue"
  import recommend from "@/components/recommend.vue"
  import footers from "@/components/footers.vue"
  import navigation from "@/components/navigation.vue"
  export default {
      name: "Main",
      components :{
          foods,
          foodrink,
          coffacke,
          recommend,
          footers,
          navigation
      }
  }
  </script>
  
  <style scoped>
  
  </style>