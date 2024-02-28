<script>
    export default{
        name: 'hero'
    }
</script>

<template>

<div class="container">
        <h2>LET'S PUSH THIS USELESS BUTTON</h2>
        <button>Premi per il nulla cosmico</button>
        <p id="txt">
            Fa sempre bene premere un pulsante inutile
        </p>
        
    </div>

</template>



<style>
.container{
    width: 500px;
    border-radius: 15px;
    background-color: bisque;
    
    padding: 15px 40px;
    margin: auto;
    font-size: 20px;
}
h2{
    font-style: italic;
    color: brown;
}
#txt{
    color: brown;
}
button{
    border-radius: 25px;
    background-color:brown;
    border: none;
    color: #ffffff;
    padding: 12px 30px;
    font-size: 15px;
    font-weight: bold;
    margin: 4px 2px;
    cursor: pointer;
    
}
</style>