<template>
    <div>
        <p>The counter is set to <b>{{counter}}</b>.</p>
        <button @click="counter += 1">Click +1</button>
        <button @click="counter -= 1">Click -1</button>
        <button @click="counter = initCounter">Reset</button>
    </div>
</template>

<script>
export default {
    name: 'LibComponentOne',
    data() {
        return {
            counter: 5,
            initCounter: 5
        };
    }
}
</script>
