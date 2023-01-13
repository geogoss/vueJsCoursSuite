<template>
    <div>
        <p class="m-5"> {{ txt }} </p>
        <liste v-bind:prenom="prenom"></liste>
    </div>
</template>

<script>

import Liste from '../Liste/Liste-formation-1.vue'

export default {
    nom: 'contenu',
    data() {
        return {
            txt: "Je suis Geoffrey Gosset",
            prenom: "Franck Lucas"
        }
    },
    components: {
        'liste' : Liste
    }
}


</script>

<style scoped src="./Contenu-formation-1.css">

</style>