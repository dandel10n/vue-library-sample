<template>
    <div>
        {{ message }}
    </div>
</template>

<script>
export default {
    name: 'LibComponentTwo',
    data () {
        return {
            number: 2
        }
    },
    computed: {
        message () {
            return `Test sample ${this.number}`;
        }
    }
}
</script>
