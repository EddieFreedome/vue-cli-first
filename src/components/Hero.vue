<template>
    <div class="main">
        <div class="jumbotron p-jumbo">
            <h1 class="p-bot">Questo e' un bel Jumbotron</h1>
            <p>Con anche la didascalia molto bella</p>
        </div>
    </div>
</template>

<script>

export default {
    name: 'Hero'    
}

</script>

<style scoped>
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

.main >div {
 margin: auto;
}

h1 {
    font-size: 50px;
    color: whitesmoke;
    font-weight: 500;
}

p {
    font-size: 20px;
}

.jumbotron{
    text-align: left;
    background-color: plum;
    max-width: 50%;
    border-radius: 10px;

}

.p-jumbo{
    padding: 50px;
}

.p-bot{
    padding-bottom: 10px;
}

</style>
