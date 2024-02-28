<script>
// prelevo il mio componente
export default {
    name: 'AppJumbo'
}

</script>

<template>
    <!-- questo verra visualizzato in pagina -->
    <div id="jumbotron">
        <div class="text_container">
            <h1 class="jumbotron_title b_color_op">
                Titolo Jumbotron
            </h1>
            <p class="jumbotron_p b_color_op">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum, quis. Nobis assumenda inventore corrupti eos aut numquam nemo aperiam atque debitis maiores fuga, ad molestias, architecto, quaerat rerum voluptas ullam.
            </p>
        </div>
        <div class="img_container">
            <img src="../assets/vue.svg" alt="vue image">
            <img src="../../public/vite.svg" alt="vite image">
        </div>
    
    </div>
</template>

<style>
#jumbotron{
    max-width: 1400px;
    margin: 0 auto;
    padding: 20px;
    display: flex;
    flex-wrap: wrap;

    background-color: #C5EBAA;
}

.b_color_op{
    color: black;
    opacity: 0.8;
}
.jumbotron_title {
    margin-bottom: 30px;
}
.jumbotron_p {
    padding: 0 20px;
}
.text_container{
    max-width: 1000px;
}
.img_container{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-grow: 1;
    gap: 20px;
}
.img_container img{
    height: 100px;
}
</style>