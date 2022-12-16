<template>
    <div id="main-banner">
        <h1>Stake Burger</h1>
    </div>
</template>

<script>
    export default{
        name:'Banner'
    }
</script>

<style scoped>

#main-banner{
    background-image: url('/public/img/burger.jpg');
    background-position:  0px -420px;
    background-size: cover;
    height: 600px;
    display: flex;
    align-items: center;
}
#main-banner h1{
 color: #f3b01f;
 text-align:  center;
 font-size: 60px;
 background-color: rgba(34, 34, 34, 0.479);
 border-radius: 5px;
 padding: 20px 40px;
}
</style>