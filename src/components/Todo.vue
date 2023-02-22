<template>
    <div>
       <Todo/>
       <input type="text">
       <button> Add </button>
    </div>
</template>

<script>
import Todo from "./components/Todo.vue";

export default {
    components:{Todo}
}

</script>

<style lang="scss" scoped>

</style>