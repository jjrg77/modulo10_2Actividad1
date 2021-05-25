<template>
    <div class="Hijo">
        <p>{{ message }}</p>
    </div>
</template>

<script>
export default {
    data () {
        return {
            message: 'Soy el componente hijo'
        }
    },
}
</script>

<style scoped>
    p {
        color: red;
        background: lightgrey;
    }
</style>