<template>
  <NavBar></NavBar>
  <SignUp/>
</template>

<script>
import NavBar from "@/components/NavBar.vue";
import SignUp from "@/components/SignUp.vue";
import { defineComponent } from "vue";

// Components

export default defineComponent({
  name: "HomeView",

  components: {
    SignUp,
    NavBar
},
});
</script>
