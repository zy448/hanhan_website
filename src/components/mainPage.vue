<template>
<div>
  <div class="main">
    <img src="../assets/mainlogo.jpg" alt="" class="main_logo">
    <span class="heading">hxxkedd</span>
    <img src="../assets/searchIcon.png" alt="" class="search">
    <img src="../assets/cart.png" alt="" class='cart'>
  </div>
  
  <div class="navigation_bar">
    <span class="shop dropdown">shop
      <div class="dropdown-content">
        <div class="all"><a href="">shop all</a></div>
        <div class="accessories"><a href="accessories.vue">accessories</a></div>
        <div class="bags"><a href="">bags</a></div>
      </div>
    </span>

    <span class="sales">sales</span>
    <span class="contact">contact</span>
    <span class="about">about us</span>
  </div>

  <div class="content">
    <img src="../assets/product1.jpg" alt="" class="product">
    <img src="../assets/product2.jpg" alt="" class="product">
    <img src="../assets/product3.jpg" alt="" class="product">
    <img src="../assets/product4.jpg" alt="" class="product">
    <img src="../assets/product5.jpg" alt="" class="product">
    <img src="../assets/product6.jpg" alt="" class="product">
  </div>
</div>
  
</template>

<script>

export default {
  name: 'mainpage',
  data() {
    return {
    }
  },
  methods: {
    display(){
    }
  },
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.main_logo {
  border-radius: 50%;
  width:5%;
  margin-top:1%;
  margin-left:1%;
  margin-bottom:1%;
  display: flex;
}
.main {  
  display: flex;
  text-align:center;
  align-content: center;
  align-items:center;

}
.heading {
  font-size:2vw;
  margin-left:40%;
  font-family: cursive;
}

.search {
  width:1.5%;
  margin-left: 40vw;
}

.cart {
  width:1.7%;
  margin-left:1vw;
}

.shop, .sales, .contact, .about{
  margin:6.9vw;
  padding-left:2%;
  padding-right:2%;
  min-width: 10vw;
}

.shop:hover, .sales:hover, .contact:hover, .about:hover{
  border:1px gray solid;
}

.dropdown-content {
  display: none;
  position: absolute;
  min-width: 10vw;
  z-index: 1;
  margin-left:14vw;
  background-color:white;
}

.dropdown:hover .dropdown-content {
  display: block;
}

.all, .accessories, .bags, .about{
  padding:1vh;
}

a {
  color:black;
}

.product {
  width:20vw;
  margin:5vw;
}
</style>
