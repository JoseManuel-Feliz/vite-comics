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
                        <li><a href="#">Shop DC </a></li>
                        <li><a href="#">Shop DC Collectibles</a></li>
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

                    <ul>
                        <li></li>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC Kids</a></li>
                        <li><a href="#">DC Universe</a></li>
                        <li><a href="#">DC Power Visa</a></li>
                    </ul>
                </nav>
            </div>

            <div class="">
                <a href="#" class="btn">SIGN-UP NOW!</a>

                <div>
                    <ul>
                        <li></li>
                        <li><a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/img/footer-twiter" alt=""></a></li>
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

        background-image: url('../assets/img/dc-logo-bg.png'), url('../assets/img/footer-bg.jpg');
        background-repeat: no-repeat, no-repeat;
        background-size: 30%, cover;
        background-position: right center, 0 0;

        .wrapper {
            display: flex;
            justify-content: space-around;

            .footer-navbar {
                display: flex;

                ul {
                    display: flex;
                    flex-direction: column;

                    li {

                        a {
                            color: lightgray;
                        }
                    }
                }
            }

            .footer-logo {}
        }
    }
}
</style>