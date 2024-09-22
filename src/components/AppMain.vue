<script>
export default {
    data() {
        return {

        }
    }
}

</script>

<template>
    <main>

        <section>
            <div class="content-wrapper">
                <p class="main-content">--> content goes here <-- </p>
            </div>
        </section>

        <section class="wrapper main-navbar">
            <nav class="main-navbar">
                <ul>

                    <li><a href="#"><img src="../assets/img/buy-comics-digital-comics.png" alt="">
                            <p>DIGITAL COMICS</p>
                        </a>
                    </li>
                    <li><a href="#"><img src="../assets/img/buy-comics-merchandise.png" alt="">
                            <p>DC MERCHANDISE</p>
                        </a></li>
                    <li><a href="#"><img src="../assets/img/buy-comics-subscriptions.png" alt="">
                            <p>SUBCRUPTION</p>
                        </a></li>
                    <li><a href="#"><img src="../assets/img/buy-comics-shop-locator.png" alt="">
                            <p>COMIC SHOP LOCATOR</p>
                        </a>
                    </li>
                    <li><a href="#"><img class="w-60" src="../assets/img/buy-dc-power-visa.svg" alt="">
                            <p>DC POWER VISA</p>
                        </a></li>
                </ul>
            </nav>
        </section>
    </main>
</template>

<style scoped>
main {

    display: flex;
    flex-direction: column;

    section {
        flex-grow: 1;



        .content-wrapper {
            margin: 0 auto;
            max-width: 1200px;
            height: 150px;
            display: flex;
            align-items: center;

            p {
                font-size: 2rem;
                color: #fff;
            }
        }
    }

    .wrapper.main-navbar {
        background: #0182F9;

        .main-navbar {
            max-width: 1200px;
            margin: 0 auto;


            ul {
                display: flex;
                height: 150px;



                li {
                    flex-basis: calc(100% / 5);
                    display: flex;
                    justify-content: space-around;
                    align-items: center;

                    a {
                        display: flex;
                        height: 50px;

                        p {
                            align-self: center;
                            color: #fff;
                            margin-left: 10px;
                            font-size: 18px;
                        }
                    }
                }
            }
        }

        .w-60 {
            width: 60px;
        }
    }
}
</style>