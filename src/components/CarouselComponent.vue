<script setup>
import { Carousel } from 'flowbite-vue'
const pictures = [
    {
        'src': './src/assets/images/disc.jpg',
        'alt': 'Picture 1',
    },
    {
        'src': './src/assets/images/kids.jpg',
        'alt': 'Picture 2',
    },
    {
        'src': './src/assets/images/under.jpg',
        'alt': 'Picture 3',
    },
    {
        'src': './src/assets/images/luxury.jpg',
        'alt': 'Picture 4',
    },
]
</script>
<template>
    <Carousel :pictures="pictures"></Carousel>
</template>
