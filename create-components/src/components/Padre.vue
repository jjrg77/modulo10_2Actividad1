<template>
    <div class="Padre">
        <p>{{ message }}</p>

        <Hijo/>
    </div>
</template>

<script>

import Hijo from '@/components/Hijo.vue'

export default {
    data () {
        return {
            message: 'Soy el componente padre'
        }
    },

    
    components: {
        Hijo
    }
}
</script>


<style scoped>
    p {
        color: blue;
        background: grey;
    }
</style>


