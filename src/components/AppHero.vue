<script>
// prelevo il mio componente
export default {
    name: 'AppJumbo'
}

</script>

<template>
    <!-- questo verra visualizzato in pagina -->
    <div id="jumbotron">
        <h1 class="jumbotron_title">
            Titolo Jumbotron
        </h1>
    
        <p class="jumbotron_p">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum, quis. Nobis assumenda inventore corrupti eos aut numquam nemo aperiam atque debitis maiores fuga, ad molestias, architecto, quaerat rerum voluptas ullam.
        </p>
    </div>
</template>

<style>

#jumbotron{
    max-width: 1400px;
    margin: 0 auto;
    padding: 20px;

    background-color: #C5EBAA;
}
.jumbotron_title, .jumbotron_p{
    color: black;
    opacity: 0.8;
}
.jumbotron_title {
    margin-bottom: 30px;
}
.jumbotron_p {
    padding: 0 20px;
}
</style>