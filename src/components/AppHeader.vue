<script>
export default {
    data() {
        return {

        }
    }

}

</script>

<template>

    <header>
        <div class="container">

            <!-- IMG LOGO DC COMICS -->
            <div class="logo-wrapper">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>

            <!-- NAVBAR  -->
            <div class="navbar">
                <nav>
                    <ul>
                        <li><a href="#">CHARACTERS</a></li>
                        <li><a href="#">COMICS</a></li>
                        <li><a href="#">MOVIES</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">GAMES</a></li>
                        <li><a href="#">COLLECTIBLES</a></li>
                        <li><a href="#">VIDEOS</a></li>
                        <li><a href="#">FANS</a></li>
                        <li><a href="#">NEWS</a></li>
                        <li><a href="#">SHOP</a></li>
                    </ul>
                </nav>
            </div>

        </div>
    </header>
</template>

<style scoped>
header {
    background: #fff;

    .container {

        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 150px;

        .logo-wrapper {
            width: 80px;

            img {
                width: 100%;
            }
        }

        ul {
            display: flex;

            li {
                margin: 0 10px;

                a {
                    font: 800 12px Arial;
                    color: #636363;

                    &:hover,
                    &.active {
                        color: #0182F9;
                    }

                }
            }
        }
    }

}
</style>