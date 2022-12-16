<template>
    <div>
       <p>Menssagem</p> 
       <div>
        <form id="burger-form">
            <div id="input-container">
                <label for="nome">Nome do cliente:</label>
                <input type="text" id="nome" name="nome" v-model="nome" placeholder="Digite seu nome">
            </div>

            <div id="input-container">
                <label for="pao">Escolha o pão:</label>
                <select name="pao" id="pao" v-model="pao"></select>
                <option value="">Selecione o seu pão</option>
                <option value="">Integral</option>
                
            </div>

        </form>
       </div>
    </div>
</template>

<script>
    export default{
        name:'BurgerForm'
    }
</script>

<style>

</style>