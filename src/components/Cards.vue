<script>
 export default {}
</script>

<template>
    <div class="card">
        <div class="card-header">
            <h2>I'm a Card!</h2>
        </div>
        <div class="card-body">
            <span>This is the body of the card</span>
        </div>
        <div class="card-footer">
            <span>Button component should be here</span>
        </div>
    </div>
</template>

<style>
.card {
    height: 200px;
    width: 150px;
}
.card-header > h2 {
    color: blueviolet;
}

.card-body > span{
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-size: medium;
}
</style>