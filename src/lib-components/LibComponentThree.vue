<template>
    <div>
        {{ message }}
    </div>
</template>

<script>
export default {
    name: 'LibComponentThree',
    data () {
        return {
            number: 3
        }
    },
    computed: {
        message () {
            return `Test sample ${this.number}`;
        }
    }
}
</script>
