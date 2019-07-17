<template>
  <div id="about">
    <img id="estarlogo" src="../assets/estarlogo.png" alt="estar logo">
    <h5 id="estartitle">易星</h5>
    <AboutCell id="about-cell" v-for="content in contents" :key="content.id" :content="content"/>
  </div>
</template>

<script>
import AboutCell from '@/components/AboutCell.vue'
export default {
  name: 'about',
  components: {
    AboutCell
  },
  data:function() {
    return {
      contents:[
      {
        leftLab: "包号",
        rightLab: "000734"
      },
      {
        leftLab: "即时行情",
        rightLab: "120.136.160.83:55013"
      },
      {
        leftLab: "历史行情",
        rightLab:"212.21.23.23.23.43"
      },
      {
        leftLab: "云交易地址",
        rightLab: "43.4.45.544.344.3343"
      }
    ]
    }
    
  }
}
</script>


<style>
#about {
  width: 100%;
  height: 100%;
  background: gray;
}
#estarlogo { 
  width: 20%;
  height: 20%;
}
#estartitle {
  font-size: 16px;
}
#about-cell {
  width: 100%;
  height: 40px;
  border-top: 1px solid rgba(7, 17, 27, 0.1);
  border-bottom: 1px solid rgba(7, 17, 27, 0.1);
}
</style>
