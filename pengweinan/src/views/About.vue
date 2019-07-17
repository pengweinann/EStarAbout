<template>
  <div class="about">
    <img id="estarlogo" src="../assets/estarlogo.png" alt="estar logo">
    <h5 id="estartitle">易星</h5>
    <AboutCell id="about-cell" />
  </div>
</template>

<script>
import AboutCell from '@/components/AboutCell.vue'
export default {
  name: 'about',
  components: {
    AboutCell
  }
}
</script>


<style>
#estarlogo { 
  width: 20%;
  height: 20%;
}
#estartitle {
  font-size: 16px;

}
#about-cell {
  padding-top: 50px;
  width: 100%;
  height: 50px;
}
</style>
