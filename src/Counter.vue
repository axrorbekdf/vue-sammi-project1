<template>
    <div class="container">
        <h1>Counter: {{counter}}</h1>
        <div class="btn-group">
            <button class="btn btn-primary" @click="increment">+</button>
            <button class="btn btn-danger" @click="decrement">-</button>
        </div>
    </div>
</template>

<script>
    export default {
        data(){
            return {
                counter: 0
            }
        },
        methods: {
            increment(){
                this.counter ++;
            },
            decrement(){
                this.counter --;
            }
        }
    }
</script>