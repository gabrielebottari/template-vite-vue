<script>
export default {
    data() {
        return {
            title: 'ciao ragazzi'
         }
    },
    template: `<div>count is {{ count }}</div>`,
};
</script>

<template>
    <div>
        <header>
            <h1 class="main-title">
                {{ title }}
            </h1>
        </header>
    </div>

</template>

<style scoped>
    header {
        padding: 20px;
        background-color: aquamarine;
    }
</style>
