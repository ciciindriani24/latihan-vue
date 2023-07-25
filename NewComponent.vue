<template>
    <MyComponent nama="cici" umur="17" alamat="Cibogo"></MyComponent>
    <Headers s="header"></Headers>
    <LatihanComponent name="cici" age="20"></LatihanComponent>
    <latihanDuaComponenet></latihanDuaComponenet>
    <WatchersComponent nama="cici" umur="17"></WatchersComponent>
</template>

<script setup>
import MyComponent from './MyComponent.vue';
import LatihanComponent from './LatihanComponent.vue';
import Headers from './Headers.vue';
import latihanDuaComponenet from './latihanDuaComponenet.vue';
import WatchersComponent from './WatchersComponent.vue'
</script>