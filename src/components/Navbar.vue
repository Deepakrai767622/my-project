<template>
  <nav>
     <ul>
         <li><a href="#">Home</a></li>
         <li><a href="#">About</a></li>
         <li><a href="#">Services</a></li>
     </ul>
  </nav>
</template>

<script>

export default {
  name: 'Navbar',
  data(){
      return{

      }
  }
};
</script>

<style>
  nav {
      text-align: center;
  }

  nav ul {
      padding: 0;
      list-style-type: none;
  }

  nav ul li {
      display: inline-block;
      list-style-type: none;
      margin: 0;
      padding: 20px;
  }

  nav ul li a {
      text-decoration: none;
  }
</style>
