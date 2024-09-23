<script>
export default {
    data() {
        return {
            navbarLinks: [
                {
                    label: "CHARACTERS",
                    url: "#",
                    active: "false",
                },
                {
                    label: "COMICS",
                    url: "#",
                    active: "false",
                },
                {
                    label: "MOVIES",
                    url: "#",
                    active: "false",
                },
                {
                    label: "TV",
                    url: "#",
                    active: "false",
                },
                {
                    label: "GAMES",
                    url: "#",
                    active: "false",
                },
                {
                    label: "COLLECTIBLES",
                    url: "#",
                    active: "false",
                },
                {
                    label: "VIDEOS",
                    url: "#",
                    active: "false",
                },
                {
                    label: "FANS",
                    url: "#",
                    active: "false",
                },
                {
                    label: "NEWS",
                    url: "#",
                    active: "false",
                },
                {
                    label: "SHOP",
                    url: "#",
                    active: "false",
                },
            ]

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
                        <li v-for="link in navbarLinks"><a :href="link.url">{{ link.label }} </a> </li>
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