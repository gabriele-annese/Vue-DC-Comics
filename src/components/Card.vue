<template>
  <div>
       <div class="img-ctn">
            <img :src="src" :alt="alt">
            <a href="/">{{title}}</a>
        </div>
  </div>
</template>

<script>
export default {
    name: 'Card',
    props: {
        src: String,
        alt: String,
        title: String,
    },
}
</script>

<style lang="scss" scoped>
     .img-ctn{
                width: 100%;
                padding-bottom: 20px;
                a{
                text-decoration: none;
                color: #fff;
                font-weight: 700;
                }
                img{
                    width: 100%;
                    height: 100%;
                    object-fit: cover;
                }
            }
</style>