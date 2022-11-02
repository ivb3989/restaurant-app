<template>
    <div>
        <slot name="header" />
        <div>
            <img src="https://cdn-icons-png.flaticon.com/512/3747/3747004.png" alt="">
        </div>
        <slot name="redirectEl" />
    </div>
</template>

<style scoped>
img {
    width: 10rem;
}
</style>