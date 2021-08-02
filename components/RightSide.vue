<template>
    <div class="fundo">
        <div class="fundo2">
            <img src="@/assets/girl-img.svg" alt="funding-kids-future" class="kid-img">
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    .fundo {
        background: url('@/assets/bubble.svg') no-repeat 50%;
        background-size: contain;
    }
    .fundo2 {
        background: url('@/assets/bubble-border.svg') no-repeat 50% 90%;
        background-size: 90%;
    }
    .kid-img {
        width: 100%;
    }
</style>