<script>
import AppHeader from './components/AppHeader.vue'

export default {
    data() {
        return { count: 0 }
    },
    template: `<div>count is {{ count }}</div>`,
    components: {
        AppHeader
    }
};
</script>

<template>
    <div>
        <AppHeader />
        <h1>
            Ciao ragazzi
        </h1>
        <p>
            {{ count }}
        </p>
        <button @click="count++">
            incrementa count
        </button>
    </div>

</template>

<style scoped>

</style>
