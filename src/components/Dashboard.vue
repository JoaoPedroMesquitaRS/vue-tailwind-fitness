<template>
    <div class="flex flex-col justify-center items-center">
        <div class="items-center justify-center w-full ml-20" id="main">
            <MainDash />
            <Facts />
        </div>
    </div>
</template>

<script>

import MainDash from './MainDash.vue'
import Facts from './Facts.vue'

export default{
    name: 'Dashboard',
    components: {
        MainDash,
        Facts
    }
}

</script>

<style scoped>



</style>