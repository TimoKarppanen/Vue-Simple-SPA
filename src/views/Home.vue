<script>
import Abstractview from "@/components/Abstractview.vue";
export default {
  name: "Home",
  components: {
    Abstractview
  }
};
</script>
<template>
    <div id="hello">
      <Abstractview msg="Hello"/>
      <Abstractview txt="Lorem Ipsum is simply dummy text of the printing and typesetting industry.
                 Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,
                  when an unknown printer took a galley of type and scrambled it to make a type specimen book.
                   It has survived not only five centuries, but also the leap into electronic typesetting,
                    remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages,
                     and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum" />
      <div class="vue-logo">
        <img alt="Vue logo" width="300" height="300" src="../assets/vue-logo.png"/>
      </div>
    </div>
  </template>

