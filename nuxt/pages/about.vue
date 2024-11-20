<template>
    <div>
        <h2>About</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus asperiores architecto iusto ut, modi eveniet voluptates ratione! Illum, error labore.</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus asperiores architecto iusto ut, modi eveniet voluptates ratione! Illum, error labore.</p>
        <div>{{ data }}</div>
    </div>
</template>

<script setup>
    const {data} = await useFetch('/api/ninja')
</script>

<style scoped>
h2{
    margin-bottom: 20px;
    font-size: 36px;
}
p{
    margin: 20px 0;
}
</style>