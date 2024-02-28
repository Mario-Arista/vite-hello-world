<script>

import AppTitle from '../components/AppTitle.vue';

export default {

    name: 'AppHero',

    components: {
        AppTitle,
    },

    data() {
    return  {

      paragrafo: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam sit voluptatibus assumenda blanditiis dolorem dolorum amet delectus, deleniti eius, ratione iusto minus quas est enim aperiam fuga doloribus. Magni, consectetur.",
        bottone: "Bottone Random",
    }

  }
}

</script>

<template>

    <div class="container">
        <AppTitle></AppTitle>
        <p>{{ paragrafo }}</p>
        <button>{{ bottone }}</button>
    </div>

</template>

<style>

.container {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 20px;

    margin: 60px auto;
    max-width: 800px;

    padding: 20px;

    border-radius: 10px;
    border: 1px solid greenyellow;

    background-color: rgba(0, 0, 0, 0.248);
    
}

.container p {
    text-align: center;
}

.container button {
    padding: 12px 18px;

    border-radius: 4px;
    border: 1px solid greenyellow;

    color: greenyellow;
    background-color: transparent;
    
}

</style>