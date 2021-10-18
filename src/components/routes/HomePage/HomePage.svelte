<script >
  import { Link } from "svelte-navigator";
  import BurgerMenu from 'svelte-burger-menu';

  

  let burgerColor = "#efb366";
  let backgroundColor = "#264653";
  let menuColor = "#f8e7c9";


  
</script>

<div class="home-page">

  <BurgerMenu  {burgerColor} {backgroundColor} {menuColor}>
    <Link to="post">Articoli</Link>
  
</BurgerMenu>
 <p>Home page</p>

 <div class="image"></div>
  

</div>


<style >
 
 .image {
    position: absolute;
    height: 100%;
    width: 100%;
    
    top: 0;
    background-image: url("public/images/blog-home-bg.jpg");
    z-index: -1;
  }
</style>