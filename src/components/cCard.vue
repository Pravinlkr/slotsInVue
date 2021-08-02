<template>
    <div class="cardBox">
        <slot name="Header"><img src="../assets/default.jpg" alt="default Image"></slot>
        <slot name="Title"><h3>Card Title</h3></slot>
        <slot name="Body"><p>Some quick example text to build on the card title and make up the bulk of card's component.</p></slot>
        <slot name="Footer"><button>Go somewhere</button></slot>
    </div>
</template>
<script>
export default{
    name:'cCard'
}
</script>
<style>
.cardBox{
    width:23%;
    margin:5% 5%;
    height: auto;
    border:1px solid #ccc;
}
.cardBox img{
    width:100%;
    height:150px;
}
.cardBox h3{
    margin: 2%;
    margin-left: 4%;
}
.cardBox p{
    margin:1% 4%;
    font-size: 15px;
    color: #454545;
}
.cardBox button{
    background-color: #339ce8;
    color:white;
    border:none;
    padding:5px 8px;
    height: 30px;
    margin:3% 4%;
    border-radius: 5px;
}
</style>
