<template>
  <div class="about">
    <h1>HELLO {{ their_name }}, WELCOME TO THE ABOUT PAGE!</h1>
    <p>This page is about the skills listed by the user possess. List all the skills you have here.</p>
  </div>
</template>

<script>
export default {  
  name: 'Skills',
 data(){
   return {
       their_name: this.$route.params.name
   }
 }
}

</script>