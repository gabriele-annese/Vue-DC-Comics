<template>
    <header>
        <nav class="container">
        <div class="img-ctn">
            <img src="../assets/dc-logo.png" alt="dc brand">
        </div>
        <ul>
            <li v-for="(link, index) in NavLink" :key="`link-${index}`" >
                <a href="#">{{link.text}}</a> 
            </li>
        </ul>
    </nav>
    </header>
</template>

<script>
export default {
    name: 'Header',
    data() {
        return {
            NavLink: [
                {
                    text:'Characters',
                    url: '/',
                    current: true,
                },
                {
                    text:'Comics',
                    url: '/',
                    current: true,
                },
                {
                    text:'Movies',
                    url: '/',
                    current: true,
                },
                {
                    text:'Tv',
                    url: '/',
                    current: true,
                },
                {
                    text:'Gamese',
                    url: '/',
                    current: true,
                },
                {
                    text:'Collectibles',
                    url: '/',
                    current: true,
                },
                {
                    text:'Videos',
                    url: '/',
                    current: true,
                },
                {
                    text:'Fans',
                    url: '/',
                    current: true,
                },
                {
                    text:'News',
                    url: '/',
                    current: true,
                },
                {
                    text:'Shop',
                    url: '/',
                    current: true,
                },
            ]
        }
    }

}
</script>

<style lang="scss" scoped>
    .container{
        width: 80%;
        height: 100px;
        margin: 0 auto;
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 10px 20px;
        .img-ctn{
            height: 80px;
            width: 80px;
            img{
                width: 100%;
                height: 100%;
            }
        }
        ul{
            display: inline-block;
            list-style: none;
            display: flex;
            .active{
                position: relative;
                bottom: 0;
                width: 20px;
                height: 30px;
                background-color: blue;
            }
            a{
                text-decoration: none;
                color: #000;
                margin-right: 25px;
                font-weight: 700;
                &:hover,
                &:focus{
                    color: #0282f9;
                }
            }
        }
    }
</style>