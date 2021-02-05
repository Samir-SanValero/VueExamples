<template>
    <h2>
        Editando usuario {{ id }}
    </h2>

    <!-- https://github.com/ohierro/training-daw-2020-projects -->
</template>

<script>
export default {
    data() {
        return {
            id: 45
        }
    },
    created() {
        this.id = this.$route.params.id
    }
}
</script>

<style>

</style>