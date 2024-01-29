<script>
import CardDisplay from './CardDisplay.vue';
export default {
    components: {
        CardDisplay
    }
}
</script>

<template>
    <div class="content">
        <div class="top"></div>
        <CardDisplay class="card" />
    </div>
</template>

<style scoped>
.content {
    position: relative;
    height: 100vh;
    width: 100%;
}

.top {
    height: 400px;
    width: 100%;
    background-color: #FDE2FF;
}

.card {
    position: absolute;
    top: 50%;
    left: 50%;
    background-color: transparent;
    transform: translate(-50%, -50%);
}
</style>