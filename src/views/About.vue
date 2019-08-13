<template>
  <div class="about">
    <h1>This is an about page</h1>
    <ApolloExample></ApolloExample>
  </div>
</template>
<script lang="ts">
import Vue from "vue";
import Component  from 'vue-class-component';
import ApolloExample from '@/components/ApolloExample.vue';
@Component({
  components: ApolloExample
})
export default class About extends Vue {

}
</script>
