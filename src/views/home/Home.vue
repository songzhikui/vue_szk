<template>
<div class="home">
    <home-header msg="this is HomeHeader"></home-header>
</div>
</template>

<script>
// @ is an alias to /src
import HomeHeader from '@/views/home/components/Header.vue'

export default {
    name: 'Home',
    components: {
        HomeHeader
    }
}
</script>
