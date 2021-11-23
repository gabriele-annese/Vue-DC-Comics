<template>
  <div class="container-footer">
      <div class="list-footer">
        <ul>
            <h4>
                Dc Comics
            </h4>
            <li>
                <a href="#">Characters</a>
            </li>
            <li>
                <a href="#">Comics</a>
            </li>
            <li>
                <a href="#">Movies</a>
            </li>
            <li>
                <a href="#">Tv</a>
            </li>
            <li>
                <a href="#">Games</a>
            </li>
            <li>
                <a href="#">Videos</a>
            </li>
            <li>
                <a href="#">News</a>
            </li>
            <h4>
                Shop
            </h4>
            <li>
                <a href="#">Shop Dc</a>
            </li>
            <li>
                <a href="#">Shop Dc Collectibles</a>
            </li>
        </ul>
        <ul>
            <h4>
                Dc 
            </h4>
            <li>
                <a href="#">Terms Of use</a>
            </li>
            <li>
                <a href="#">Privacy policy (New)</a>
            </li>
            <li>
                <a href="#">Ad Choices</a>
            </li>
            <li>
                <a href="#">Advertising</a>
            </li>
            <li>
                <a href="#">jobs</a>
            </li>
            <li>
                <a href="#">Subscriptions</a>
            </li>
            <li>
                <a href="#">Talent Workshops</a>
            </li>
            <li>
                <a href="#">CPSC Certificates</a>
            </li>
            <li>
                <a href="#">Reatings</a>
            </li>
            <li>
                <a href="#">Shop Help</a>
            </li>
            <li>
                <a href="#">Contact Us</a>
            </li>
        </ul>
        <ul>
            <h4>
               Sites
            </h4>
            <li>
                <a href="#">DC</a>
            </li>
            <li>
                <a href="#">MAD Magazine</a>
            </li>
            <li>
                <a href="#">DC kids</a>
            </li>
            <li>
                <a href="#">DC Universe</a>
            </li>
            <li>
                <a href="#">DC Power Vista</a>
            </li>
        </ul>
      </div>
      <div class="img-container">
          <img src="../assets/dc-logo-bg.png" alt="">
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .container-footer{
        width: 100%;
    
        background-image: url(../assets/footer-bg.jpg);
        display: flex;
        .list-footer{
            margin-top: 20px;
            width: 50%;
            height: 30px;
            display: flex;
            justify-content: space-around;
        ul{
            list-style: none;
            color: #fff;
            h4{
                margin-top: 20px;
                text-transform: uppercase;
                font-weight: 700;
                font-size: 20px;
                margin-bottom: 10px;
            }
            li{
                padding: 3px 0;
            }
            a{
                text-decoration: none;
                color: lightgray;
                font-size: 14px;
            }
        }
        }
        .img-container{
            width: 50%;
            height: 400px;
            img{
                width: 100%;
                height: 100%;
                object-fit: contain;
            }
        }

    }
</style>