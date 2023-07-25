<template>
    <div>
        <h1>Hallo Dunia</h1>
        <p>Ini komponen gue</p>
        <!-- props -->
        <h2>Nama : {{ nama }}</h2>
        <p>Umur : {{ umur }}</p>
        <p>Alamat : {{ alamat }}</p>
    </div>
</template>

<script>
export default {
    name: "MyComponent",
    props: ['nama', 'umur', 'alamat'],
    data() {
        return {
            message : "Ini pesan dari komponen"
        }
    },
    methods: {
        greet() {
            console.log("Haloo");
        }
    },
}
</script>

<style>
h1 {
    color: burlywood;
}

p {
    size: 16px;
}
</style>