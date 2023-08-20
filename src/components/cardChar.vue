<script setup lang="ts">
</script>
<template>
    <div class="card">
        <div class="tittle">
            <img class="photochar" src="" alt="imagem do usuario">
            <h1 class="nickName">XdougD</h1>
        </div>
        <div class="description">
            <h2 class="guildName">*dinamos*</h2>
            <div class="stacks">
                <h3>abilidades:</h3>
                <p>
                    <span>vue </span>
                    <span>react</span>
                </p>
                
            </div>
            <h4 class="ranking"></h4>
        </div>
        <a href="/">mais</a>
    </div>
</template>
<style scoped>
    .card {
        background: linear-gradient( to bottom right ,var(--color-1) 33%, var(--color-2) 66%, var(--color-3) 90%);
        width: 35%;
        margin: 5px;
        padding: 15px 5px;
        max-width: 320px;
        border-radius: 15px;
        text-align: center;
        min-width: 250px;
    }
    .tittle {
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
    }
    .photochar{
        background-color: var(--color-5);
        border-radius: 10%;
        padding: 80px;
        width: 80%;
    }
    .description{
        margin: 5px;
    }
    .description h2{
        font-style: italic;
    }
    .card a{
        color: #000;
        text-decoration: none;
        background-color: var(--color-4);
        padding: 7px;
        border-radius: 10px;
        
    }
    .card a:hover{
        background-color: var(--color-5);
        background: linear-gradient(#ccc 30%, var(--color-2) 60%, var(--color-3) 90%);
    }
</style>