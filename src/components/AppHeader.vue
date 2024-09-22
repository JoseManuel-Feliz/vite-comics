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

    </header>
</template>

<style scoped>
header {
    background: #fff;
    display: flex;
    justify-content: space-around;
    align-items: center;

    ul {
        display: flex;

        li {
            margin: 0 10px;
        }
    }

}
</style>