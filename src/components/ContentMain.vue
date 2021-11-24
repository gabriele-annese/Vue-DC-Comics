<template>
<div>
    <div class="container">
        <button class="series">
            Current series
        </button>
    </div>
    <div class="container-content">
        <div>
            <Hero />
        </div>
    </div>
</div>
</template>

<script>
import Hero from '@/components/Hero.vue'
export default {
    name: 'ContentMain',
    components: {
        Hero,
  }

}
</script>

<style lang="scss" scoped>
    .container{
        width: 100%;
        height: 400px;
        background-image: url(../assets/jumbotron.jpg);
        background-size: cover ;
        position: relative;
        width: 100%;
        color: #fff;
            .series{
                position: absolute;
                bottom: -20px;
                left: 10%;
                background-color: #0282f9;
                color: #fff;
                text-transform: uppercase;
                font-size: 20px;
                border: 0;
                padding: 10px 10px;
            }
        .container-content{
            width: 80%;
            margin: 0 auto;
        }
    }
</style>