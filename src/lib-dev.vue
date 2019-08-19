<template>
    <div class="test-library-lib-dev">
        <lib-component-one></lib-component-one>
        <lib-component-two></lib-component-two>
    </div>
</template>

<script>
import { LibComponentOne, LibComponentTwo } from './entry';

export default {
    name:  'TestLibraryLibDev', // vue library dev component
    components: {
        LibComponentOne,
        LibComponentTwo
    },
}
</script>

<style scoped>
    .test-library-lib-dev {
        display: block;
        width: 400px;
        margin: 25px auto;
    }
</style>
