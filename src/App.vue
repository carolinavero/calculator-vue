<template>
    <div id="app">
        <h1>Calculadora</h1>
        <Calculator />
    </div>
</template>
  
<script>

import Calculator from './main/Calculator';

export default {
    components: { Calculator }
}

</script>

<style>

@font-face {
    font-family: "RobotoMono";
    src: url('./fonts/RobotoMono-Thin.ttf');
}

* {
    font-family: 'RobotoMono', monospace;
}

body {
    margin: 0;
}

#app {
    display: flex;
    flex-direction: column;
    height: 100vh;
    width: 100vw;
    justify-content: center;
    align-items: center;
    text-align: center;

    color: #fff;
    background-color: #42b883;
}

</style>