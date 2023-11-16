<template>
  <InputName v-model:name="parentName"/>
  {{ parentName }}
</template>

<script>
import InputName from './components/InputName.vue';

  export default{
    name: "App",
    data(){
      return{
        parentName : ""
      }
    },
    components: { InputName }
}
</script>
<style scoped>

</style>
