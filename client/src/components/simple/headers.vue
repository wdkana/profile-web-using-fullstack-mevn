<template>
<b-col cols="12" md="8" fluid>
    <h1 style="color:#ffea9e;text-shadow: 1px 2px #fff;cursor:default">Who is 'DEA' ?</h1>
    <hr/>
    <div class="biglink text-white">
        <b-link class="linking" to="https://linkedin.com/afrizaldea" style="color:#ffea9e">LinkedIn</b-link> | 
        <b-link class="linking" to="https://twitter.com/afrizaldea" style="color:#ffea9e">Twitter</b-link> | 
        <b-link class="linking" to="https://instagram.com/afrizaldea" style="color:#ffea9e">Instagram</b-link>
    </div>
</b-col>
</template>

<script>
export default {

}
</script>

<style scoped>
    h1{
        font-size: 90px;
    }
    .linking:hover{
        text-decoration: none;
        transition: .3s;
        background: #777;
        border-radius: 80%;
    }
    .biglink{
        font-size: 24px
    }
</style>
