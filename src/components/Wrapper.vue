<template>
<div class="body">
  <Index></Index>
  <div id="bg"></div>
</div>
</template>

<script>
// eslint-disable-next-line
import MyHeader from "@/components/Header";
// eslint-disable-next-line
import Main from "@/components/Main";
// eslint-disable-next-line
import MyFooter from "@/components/Footer";
// eslint-disable-next-line
import Index from "@/components/Index";
export default {
  name: 'Wrapper',
  components: {
    MyHeader,
    Main,
    MyFooter,
    Index
  }
}
</script>

<style>

</style>
