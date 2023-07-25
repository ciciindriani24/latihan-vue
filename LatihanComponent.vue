<template>
    <div v-if="age > 18">
        <p>Selamat Datang {{ name }}</p>
    </div>
    <div v-else>
        <p>Maaf Belum Cukup Umur</p>
    </div>
    <button @click="great">Sapa</button>
</template>
<script>
export default {
    props: ['name', 'age'],
    methods: {
        great() {
            alert("Haloo " + this.name);
        }
    },
}
</script>