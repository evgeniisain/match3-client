<template>
    <div>

    </div>
</template>

<script>
    import Gem from "../../entities/gem";

    export default {
        name: "gem",
        props: {
            gemData: {
                type: Gem,
                default: null,
            },
        },
    }
</script>

<style scoped>

</style>