<script setup>
import {ref} from 'vue'

const msg = "Hello World";
const rawHtml = "<li>ciciiii</li>";
const vhtml = " <li>love</li>";
let a = 10;
let b = 5;
let c = a+b

</script>

<template>
  <div :id="dynamicId" id="app">

    <h1>{{ msg }}</h1>

    <span v-html="rawHtml"></span>
    <span style="color: rgb(120, 118, 238)" v-html="vhtml"></span><br>
    <button :disabled="isButtonDisabled">Button</button><br>
    bil1={{ a }}<br>
    bil2={{ b }}<br>
    hasil={{ c }}
  </div>
</template>