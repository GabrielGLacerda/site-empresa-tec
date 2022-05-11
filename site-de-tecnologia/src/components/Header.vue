<template>
    <div>
        <nav id="nav-bar">
            <div class="content">
                <img id="logo" src="../assets/logo2.png" alt="logo">
                <ul>
                    <li><a href="/">Home</a></li>
                    <li><a href="/services">Serviços</a></li>
                    <li><a href="/about-us">Sobre nós</a></li>
                    <li><a href="/contact">Contato</a></li>
                </ul>
            </div>
        </nav>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    
})
</script>

<style scoped>
    #nav-bar {
        background-color: #F2F2F2;
        height: 160px;
        overflow: hidden;
    }

    .content {
        display: grid;
        grid-template-columns: 4fr 3fr;
        align-items: center;
    }

    ul {
        list-style: none;
        display: flex;
        padding-bottom: 50px;
    }

    a {
        text-decoration: none;
        font-weight: bold;
        font-size: 1.6rem;
        padding: 1rem;
    }

    #logo {
        height: 200px;
        width: 200px;
    }
</style>