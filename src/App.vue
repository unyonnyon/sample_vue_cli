<template>
    <div id="app">
        <Task :data="value" />
    </div>
</template>

<script>
import Task from "./components/Task.vue";

export default {
    name: "app",
    data: function() {
        return {
            value: {
                a: "apple",
                b: "banana",
                c: "orange"
            }
        };
    },
    components: {
        Task
    }
};
</script>

<style>
</style>
