<template>
    <header>
       <nav class="container">   
           <a href="/"><img alt="Inicio" title="Inicio" id="Logo" src="https://pbs.twimg.com/profile_images/1334939865197260801/TR92DJ_q_400x400.png"></a>
            <h1>logout</h1>
       </nav>  
       
    </header>
</template>

<script>
export default {
    name:'Header'
}
</script>

<style scoped>
    header{
        background-color: var(--color-background-nav);
        width: 100%;
        height: 60px;
    }
    #Logo{
        width: 60px;
        
    }
    h1{
        color: darkgray;
        font-family: Brothers;
        padding-top: 1.5%;
    }
    nav{
        display: flex;
        justify-content: space-between;
    }
</style>