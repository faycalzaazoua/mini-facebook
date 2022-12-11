<template>
    <header id="header">
        <div id="header-left">
            <img id="img-vue" src="../assets/images/vue.png" />
            <h1>MyNetWork</h1>
        </div>
        <div id="header-right">
            <h2>Social Network App for Hitema by Ayoub MOUTAOUAKIL</h2>
        </div>
    </header>
</template>

<script setup>

</script>

<style scoped>

#header {
    width: 100%;
    height: 10vh;
    background-color: #3FB984;
    display: flex;
    flex-direction: row;
}

#header-left {
    width: 50%;
    height: 100%;
    display: flex;
    flex-direction: row;
    align-items: center;
    padding-left: 30px;
}

#header-right {
    width: 50%;
    height: 100%;
    display: flex;
    flex-direction: row-reverse;
    align-items: center;
    padding-right: 10px;
}

#img-vue {
    width: 50px;
    height: 50px;
    margin-right: 10px;
}

</style>