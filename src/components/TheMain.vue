<template>
    <main>
        <section class="banner">
            <div class="card-box container">
                <ComicsCard v-for="(card,i) in cards" :key="i" :card="card"/>
            </div>
        </section>
    </main>
</template>

<script>
import ComicsCard from './ComicsCard.vue'
export default {
    name: 'TheMain',
    components: {
    ComicsCard,
    },
    props:{
        cards:Array
    }
}
</script>

<style lang="scss" scoped>

 .banner{
    background-color: black;
   .card-box{
    display: flex;
    flex-wrap: wrap;
    padding: 20px;
   }
 }
</style>