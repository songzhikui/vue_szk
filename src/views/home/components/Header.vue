<template>
<div class="header">
    <h1>{{ msg }}</h1>
</div>
</template>

<script>
export default {
    name: 'HomeHeader',
    props: {
        msg: String
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .header{
        background: #f00;
        width: 100%;
        height: 0;
        padding-bottom: 50%;
    }
</style>
