<script setup lang="ts">
</script>
<template>
    <div class="card">
        <div class="tittle">
            <div class="photochar"></div>
            <h1 class="nickName">XdougD</h1>
        </div>
        <div class="description">
            <h2 class="guildName">*dinamos*</h2>
            <div class="stacks">
                <h3>abilidades:</h3>
                <ul>
                    <li><p>react</p></li>
                    <li><p>vue</p></li>
                </ul>
            </div>
            <h4 class="ranking"></h4>
        </div>
        <a href="/">mais</a>
    </div>
</template>
<style scoped>
    .card {
        background-color: rgb(217, 217, 16);
        width: 35%;
        margin: 5px;
        padding: 10px;
        max-width: 520px;
        border-radius: 15px;
    }
    .tittle {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        padding: 10px;
    }
    .photochar{
        background-color: red;
        border-radius: 50%;
        padding: 50px;
    }
    .description{
        margin: 15px;
    }
    .description h2{
        font-style: italic;
    }
    .card a{
        color: #000;
        text-decoration: none;
        background-color: rgb(255, 170, 0);
        padding: 7px;
        border-radius: 10px;
        
    }
    .card a:hover{
        background-color: rgb(255, 221, 127);
    }
</style>