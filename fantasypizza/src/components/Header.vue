<template>
    <div>
        <h1>Fantasy Pizza</h1>
    </div>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style scoped>
    div{
        display: flex;
        justify-content: space-between;
        border-color: white;
        border-width: 0px 0px 2px 0px;
        border-style: solid;
    }

    h1 {
        color: white;
        font-family: 'Lobster', cursive;
        font-weight: 400;
        font-size: 2em;
        margin-left: 2.5%;
        margin-top: 10px;
        margin-bottom: 10px;
    }
</style>
