<template>
<div class="body">
  <div id="wrapper">
    <my-header></my-header>
    <main></main>
    <my-footer></my-footer>
  </div>
</div>
</template>

<script>
// eslint-disable-next-line
import MyHeader from "@/components/Header";
// eslint-disable-next-line
import Main from "@/components/Main";
// eslint-disable-next-line
import MyFooter from "@/components/Footer";
export default {
  name: 'Wrapper',
  components: {
    MyHeader,
    Main,
    MyFooter
  }
}
</script>

<style>

</style>
