<template>
<footer>
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
    <div class="container-social">
        <div class="bar-social">
            <button>
                sign-up now!
            </button>
            <ul>
                <li>
                    <h4>follow us</h4>
                </li>
                <li class="img-ctn">
                    <img src="../assets/footer-facebook.png" alt="">
                </li>
                <li class="img-ctn">
                    <img src="../assets/footer-twitter.png" alt="">
                </li>
                <li class="img-ctn">
                    <img src="../assets/footer-youtube.png" alt="">
                </li>
                <li class="img-ctn">
                    <img src="../assets/footer-pinterest.png" alt="">
                </li>
                <li class="img-ctn">
                    <img src="../assets/footer-periscope.png" alt="">
                </li>
            </ul>
        </div>
    </div>
    <div class="icon-ctn">
        <div class="icon-bar">
            <ul>
                <li class="img-ctn">
                    <img src="../assets/buy-comics-digital-comics.png" alt="">
                </li>
                <li>
                    <a href="#">
                        Digital Comics
                    </a>
                </li>
            </ul>
            <ul>
                <li class="img-ctn">
                    <img src="../assets/buy-comics-merchandise.png" alt="">
                </li>
                <li>
                    <a href="#">
                        Digital Comics
                    </a>
                </li>
            </ul>
            <ul>
                <li class="img-ctn">
                    <img src="../assets/buy-comics-subscriptions.png" alt="">
                </li>
                <li>
                    <a href="#">
                        Digital Comics
                    </a>
                </li>
            </ul>
            <ul>
                <li class="img-ctn">
                    <img src="../assets/buy-comics-shop-locator.png" alt="">
                </li>
                <li>
                    <a href="#">
                        Digital Comics
                    </a>
                </li>
            </ul>
            <ul>
                <li class="img-ctn">
                    <img src="../assets/buy-dc-power-visa.svg" alt="">
                </li>
               <li>
                    <a href="#">
                         Digital Comics
                    </a>
                </li>
            </ul>
        </div>
    </div>
  </div>
</footer>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .container-footer{
        width: 100%;
        height: 500px;
        background-image: url(../assets/footer-bg.jpg);
        display: flex;
        position: relative;
        .list-footer{
            margin-top: 100px;
            margin-bottom: 20px;
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
            margin-top: 50px;
            width: 50%;
            height: 450px;
            img{
                width: 100%;
                height: 100%;
                object-fit: contain;
            }
        }
    .container-social{
        width: 100%;
        background-color: #303030;
        position: absolute;
        bottom: -10px;
        .bar-social{
            width: 80%;
            margin: 0 auto;
            padding: 15px 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
            button{
                background: none;
                border: 1px solid #0282f9;
                font-weight: 700;
                text-transform: uppercase;
                padding: 8px 7px;
                color: #fff;
                &:hover,
                &:focus{
                    background-color: #027ce5;
                    cursor: pointer;
                    transition: 0.3s linear;
                }
            }
            ul{
                list-style-type: none;
                display: flex;
                align-items: center;
                li{
                    padding: 0 10px;
                    h4{
                        color: #027ce5;
                        text-transform: uppercase;
                    }
                }
                .img-ctn{
                    width: 50px;
                    height: 30px;
                    img{
                        width: 100%;
                        height: 100%;
                        cursor: pointer;
                    }
                }
            }
        }
    }
    .icon-ctn{
        width: 100%;
        position: absolute;
        top: 0;
        background-color: #0282f9;
        .icon-bar{
            width: 80%;
            margin: 0 auto;
            display: flex;
            justify-content: space-around;
            padding: 20px 0;
            ul{
                list-style-type: none;
                color: #fff;
                display: flex;
                align-items: center;
                a{
                    text-decoration: none;
                    color: #fff;
                      margin-right: 20px;
                      &:last-child{
                            margin-right: 0;
                        }
                }
                .img-ctn{
                    width: 30px;
                    height: 40px;
                    margin-right: 10px;
                    cursor: pointer;
                    img{
                        width: 100%;
                        height: 100%;
                        object-fit: contain;
                    }
                }
            }
        }
    }
    }
</style>