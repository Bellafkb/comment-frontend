<template>
  <div id="app">
    <VcAFrame title="comments">
      <VcAColumn size="90%">
        <VcABox title="comments" :first="true"></VcABox>
      </VcAColumn>
    </VcAFrame>
  </div>
</template>

<script>
import { VcAFrame, VcAColumn, VcABox, VcAInfoBox } from 'vca-widget-base'
import 'vca-widget-base/dist/vca-widget-base.css'
export default {
  name: "app",
  components: { VcAFrame, VcAColumn, VcABox, VcAInfoBox }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
