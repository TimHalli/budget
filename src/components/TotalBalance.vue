<template>
    <div class="total-value">Balance: {{ total }}</div>
</template>
<script>
    export default {
        name: 'TotalBalance',
        props: {
            total: {
                type: Number,
                default: 0,
            },
        },
    };
</script>
<style scoped>

.total-value{
    text-transform: uppercase;
    font-size: 26px;
    padding: 20px;
    text-align: 20px;
}
</style>
