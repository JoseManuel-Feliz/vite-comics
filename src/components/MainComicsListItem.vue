<script>
export default {
    data() {
        return {

        }
    },
    props: {
        comicUrl: {
            required: true,
            type: String
        },
        comicSeries: {
            required: true,
            type: String
        },
        comicPrice: {
            required: true,
            type: String
        },
        comicType: {
            required: true,
            type: String
        },
    },
}
</script>

<template>
    <li>
        <div class="comic-img wrapper">
            <img :src="comicUrl" :alt="comicSeries">
        </div>
        <p>{{ comicSeries }}</p>
    </li>
</template>

<style scoped>
li {
    flex-basis: calc(100% / 6);
    margin: 10px 0;

    .comic-img {
        max-width: 150px;
    }

    img {
        width: 100%;
        aspect-ratio: 3/4;
        object-position: left;

    }

    p {
        margin-top: 5px;
        color: #fff;
    }

}
</style>