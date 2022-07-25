<template>
    <div class="comics-card">
        <figure>
            <a href="#">
                <img :src="card.thumb" :alt="card.series">
            </a>
        </figure>
        <figcaption>
        <p>{{card.series}}</p>
        </figcaption>
    </div>
</template>

<script>
 export default {
    name:'ComicsCard',
    props:{
        card: Object
    }
 }
</script>

<style lang="scss" scoped>
    .comics-card{
        flex-basis: calc(100% / 6 - 10px);
        padding: 0 5px;

        img{
            display: block;
            max-width: 100%;
            height: auto;
        }

        figcaption{
            color: white;
            text-align: center;
        }
     }
</style>