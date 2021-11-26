<template>
    <nav class="nav">
        <a class="nav-link" >INICIO</a>
        <a class="nav-link" >DREADLOCKS</a>
        <a class="nav-link" >CONTACTO</a>
        <a class="nav-link" >LOGOS</a>
    </nav>
</template>
<script>

export default {
    name:'Nav',
}
</script>
<style scoped>
nav{
    place-self: center;
    margin-top: 2%;
    display: flex;
    justify-content: space-around;
    align-items: center;
    box-shadow:  6px 6px 12px #898989,
             -6px -6px 12px #ffffff;
    background-color: #CDA291;
    font-family: sans-serif;
}

</style>