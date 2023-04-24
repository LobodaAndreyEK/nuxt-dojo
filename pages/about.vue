<template>
    <div>
        About page
    </div>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aut perferendis enim pariatur natus iusto, dignissimos
        officia eos explicabo quia! Molestiae tempore explicabo consequuntur veniam voluptatibus eum quisquam facere
        doloremque repellat.</p>
    <div>{{ data }}</div>
</template>

<script setup>
const { data } = await useFetch('/api/currency/GBP');

</script>

<style lang="scss" scoped></style>