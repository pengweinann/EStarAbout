<template>
    <div id="about-cell">
        <div id="left">{{content.leftLab}}</div>
        <div id="right">{{content.rightLab}}</div>
    </div>
</template>

<script>
export default {
    name: 'AboutCell',
    props: {
        content: {
          leftLab:String,
          rightLab:String
        }
    }
}
</script>


<style>
#about-cell {
    width: 100%;
    background-color: white;
    border: 1;
    border-bottom-color: gray;
}
#left {
    text-align: left;
    width: 30%;
    display: inline-block;
}
#right {
    text-align: right;
    width: 60%;
    display: inline-block;
}
</style>
