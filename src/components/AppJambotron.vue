
<script>
export default {
    data() {
        return {

        }
    },
    methods: {
        getImagePath(path) {
            return new URL(path, import.meta.url)
        }
    },
}
</script>


<template>
    <div>
        <img :src='getImagePath(`../assets/imgJambo.jpg`)'>
    </div>
</template>


<style></style>