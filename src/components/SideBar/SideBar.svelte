<script>
   import { Link } from "svelte-navigator";
  import BurgerMenu from 'svelte-burger-menu';

  

  let burgerColor = "#efb366";
  let backgroundColor = "#264653";
  let menuColor = "#f8e7c9";
</script>

<BurgerMenu  {burgerColor} {backgroundColor} {menuColor}>
  <Link to="post">Articoli</Link>

</BurgerMenu>

<style></style>