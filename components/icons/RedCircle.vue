<template>
    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 621.48 573.76"
        class="red-circle">
        <defs>
            <linearGradient id="Degradado_sin_nombre_24" y1="286.88" x2="573.76" y2="286.88"
                gradientUnits="userSpaceOnUse">
                <stop offset="0" stop-color="#ff415f" />
                <stop offset="1" stop-color="#ff785e" />
            </linearGradient>
            <linearGradient id="Degradado_sin_nombre_14" x1="514.19" y1="240.07" x2="514.19" y2="18.67"
                gradientUnits="userSpaceOnUse">
                <stop offset="0" stop-color="#ffc15f" />
                <stop offset="1" stop-color="#fff687" />
            </linearGradient>
        </defs>
        <title>red-circles</title>
        <g id="Capa_2" data-name="Capa 2">
            <g id="Capa_1-2" data-name="Capa 1">
                <circle class="cls-1 move-smooth-x" cx="286.88" cy="286.88" r="286.88" />
                <circle class="cls-2 move-smooth-y" cx="514.19" cy="131.65" r="90" />
            </g>
        </g>
    </svg>
</template>

<script>
export default {
    name: 'RedCircle',
}
</script>

<style scoped>
.cls-1,
.cls-2 {
    opacity: 0.9;
}

.cls-1 {
    fill: url(#Degradado_sin_nombre_24);
}

.cls-2 {
    fill: url(#Degradado_sin_nombre_14);
}
</style>
