
<script setup>
import {ref} from "vue";
const count= ref(0);

</script>

<template>
<main>
  <div>
    <h4>
      The current count is ...
    </h4>
    <h1>
      {{count}}
    </h1>
    <button @click="count--">-</button>
    <button @click="count++">+</button>
  </div>
</main>
</template>

<style scopped>
main{
  background-color: aliceblue;
  height: 100vh;
  widows: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;

}

div{
  text-align: center;
}
button{
  margin:5px;
}
</style>