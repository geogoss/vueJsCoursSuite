<template>
    <div>
        <ul>
            <li v-for="(fruit, index) in fruits" v-bind:key="index"> {{ fruit }} </li>
        </ul>
        <p>
            {{ prenom }}
        </p>
    </div>
</template>

<script>

    export default {
        nom:'liste',
        data() {
            return {
                fruits: ['fraise', 'citron', 'mangue', 'orange']
            }
        },
        props: ['prenom']
    }

</script>

<style scoped src="./Liste-formation-1.css"></style>