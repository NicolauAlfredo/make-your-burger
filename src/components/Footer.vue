<template>
    <div id="footer">
        <p>Make Your Burger &copy; 2022 by <a href="#">Nicolau Alfredo</a></p>
    </div>
</template>

<script>
    export default {
        name: 'Footer'
    }
</script>

<style scoped>
    #footer {
        height: 200px;
        background: #222;
        border-top: 4px solid #111;
        color: #FCBA03;
        display: flex;
        align-items: center;
        justify-content: center; 
        width: 100%;
    }

    a { 
        text-decoration: none;
        background: #FCBA03;
        padding: 10px;
        color: #000;
        border-radius: 5px;
    }
</style>