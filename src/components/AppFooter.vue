<script>
export default {
    data() {
        return {

        }
    }
}

</script>

<template>
    <footer>
        <div class="bg-wrapper">

            <div class="container">

                <div class="wrapper">
                    <nav class="footer-navbar">

                        <ul>
                            <li></li>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>

                        <ul>
                            <li></li>
                            <li><a href="#">DC</a></li>
                            <li><a href="#">MAD Magazine</a></li>
                            <li><a href="#">DC Kids</a></li>
                            <li><a href="#">DC Universe</a></li>
                            <li><a href="#">DC Power Visa</a></li>
                        </ul>

                        <ul>
                            <li></li>
                            <li><a href="#">Terms Of Use</a></li>
                            <li><a href="#">Privacy police (New)</a></li>
                            <li><a href="#">Ad Choices</a></li>
                            <li><a href="#">Advertising</a></li>
                            <li><a href="#">Jobs</a></li>
                            <li><a href="#">Subscriptions</a></li>
                            <li><a href="#">Talent Workshops</a></li>
                            <li><a href="#">CPSC Certificates</a></li>
                            <li><a href="#">Ratings</a></li>
                            <li><a href="#">Shop Help</a></li>
                            <li><a href="#">Contact Us</a></li>
                        </ul>

                        <ul class="flex-grow">
                            <li></li>
                            <li><a href="#">Shop DC </a></li>
                            <li><a href="#">Shop DC Collectibles</a></li>
                        </ul>
                    </nav>
                </div>
            </div>
        </div>

        <div class="bg-grey">

            <div class="container barra">
                <a href="#" class="btn">SIGN-UP NOW!</a>

                <div class="socials-links">
                    <ul>
                        <li></li>
                        <li><a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a></li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>

<style scoped>
footer {

    .bg-wrapper {
        background: url('../assets/img/footer-bg.jpg') 0 0 / cover no-repeat;
        height: 350px;

        .container {
            height: 100%;
            max-width: 1200px;
            margin: 0 auto;
            background-image: url('../assets/img/dc-logo-bg.png');
            background-repeat: no-repeat;
            background-position: right;

            .wrapper {
                display: flex;
                padding: 40px 0;

                .footer-navbar {
                    display: flex;
                    column-gap: 15px;
                    flex-wrap: wrap;


                    ul {
                        display: flex;
                        flex-direction: column;
                        flex-basis: calc(100% / 3 - 45px / 3);



                        a {
                            font-size: small;
                            color: lightgray;
                        }

                    }
                }

            }

        }
    }

    .bg-grey {
        background-color: #303030;

        .barra {
            height: 100px;
            display: flex;
            justify-content: space-between;
            align-items: center;

            a.btn {
                font-size: 18px;
                color: #fff;
                padding: 15px;
                border: #0182F9 solid 3px;
            }

            .socials-links>ul {
                display: flex;

                li {
                    margin: 0 10px;
                }

            }
        }
    }
}
</style>