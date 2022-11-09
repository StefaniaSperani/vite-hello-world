<template>

<header>

<h1>{{titolo}}</h1>

</header>

</template>

<script>
    export default {
        name: 'AppTitle',
        data(){
            return{
                titolo: 'La mia prima app con Vite!'
            }
        }
    }
</script>

<style lang="css">
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
 header{
    width: 100%;
    height: 100px;
    background-color: brown;
    text-align: center;
    padding: 20px 0;
 }
</style>