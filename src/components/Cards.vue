<script setup>

import Button from './Button.vue';

</script>

<script>
 export default { components: { Button } }
</script>

<template>
    <div class="card">
        <div class="card-header">
            <h2>Title</h2>
        </div>
        <div class="card-body">
            <div class="card-image">
            </div>
            <span>This is the body of the card</span>
        </div>
        <div class="card-footer">
            <Button/>
        </div>
    </div>
</template>

<style>
.card {
    background-color: aliceblue;
    border-radius: 8px;
    height: 200px;
    width: 150px;
    padding: 16px 16px;
}
.card-header > h2 {
    color: rgb(42, 42, 42);
    font-size: x-large;
    font-weight: 600;
}

.card-body > .card-image {
    background-image: url("https://fujifilm-x.com/wp-content/uploads/2021/01/gfx100s_sample_04_thum-1.jpg");
    background-color: azure;
    background-size: 100%;
}

.card-body > span{
    font-size: medium;
    color: rgb(42, 42, 42);
}
</style>