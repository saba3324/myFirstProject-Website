<template>
    <div class="container">
        <Header title="Vue App" action="Get started" color="lightblue" bgColor="darkblue" />
    </div>
    <div class="container">
        <Header title="Todo list" action="Add Task" />
    </div>
</template>

<script>
import Header from './Header.vue'
export default {
    name: 'App',
    components: {
        Header
    }
}
</script>

<style>
#app {
    text-align: center;
    margin-top: 60px;
}

.container {
    border: 1px solid steelblue;
    padding: 30px;
    max-width: 500px;
    margin: 20px auto;
}
</style>
