<template>
    <div class="b">
        <button @click="add">{{num}}</button>
    </div>
</template>

<script>
export default {
    name: 'practise git',
    data() {
        return {
            data: 'v2.0',
            obj: {},
            num: 0
        }
    },
    methdos: {
        change() {
            console.log('dev-2.0 push to dev branch');
        },
        add() {
            this.num++:
        }
    }
}
</script>

<style>

</style>
