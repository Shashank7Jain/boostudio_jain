<template>
<div class="wave">
  
</div>
</template>
<script>
export default {
    name:"Curves"
}
</script>
<style scoped>
.wave {
  width: auto;
  height: 200px;
  position: relative;
}

.wave:after {
    content: '';
    width: 50%;
    position: absolute;
    height: 29px;
    display: block;
    border-bottom: 3px solid black;
    border-top-left-radius: 28%;
    border-top-right-radius: 28%;
    border-bottom-right-radius: 28%;
    border-bottom-left-radius: 28%;
    left: 50%;
}

.wave:before {
     content: '';
    width: 50%;
    position: absolute;
    height: 29px;
    display: block;
    border-top: 3px solid black;
    border-top-left-radius: 28%;
    border-top-right-radius: 28%;
    border-bottom-right-radius: 28%;
    border-bottom-left-radius: 28%;
}
</style>