<template>
    <div id="app">
        <Map/>
    </div>
</template>

<script>
    import Map from "./components/Map.vue";

    export default {
        name: "App",
        components: {
            Map
        }
    };
</script>

<style>
    #app {
        width: 1980px;
        height: 1080px;
    }

    body {
        margin: 0;
        padding: 0;
    }
</style>