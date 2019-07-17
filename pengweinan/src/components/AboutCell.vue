<template>
    <div id="about-cell">
        <div id="left">包号</div>
        <div id="right">000735</div>
    </div>
</template>

<script>
export default {
    name: 'AboutCell',
    // props: {
    //     packageNumber: string
    // }
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
