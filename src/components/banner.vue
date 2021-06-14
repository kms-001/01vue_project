<template>
    <div class="banner">
        {{text}}
    </div>
</template>

<script>
export default {
    name:'banner',
    data(){
        return{
            text:'안녕하세요 :)'
        }
    }
}
</script>

<style>
    .banner {width: 100%; height: 100px; 
            background: rgb(206, 205, 252); display: flex;
            justify-content: center; align-items: center;}
</style>