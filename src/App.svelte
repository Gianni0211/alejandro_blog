<script>
import { Router, Route, Link } from "svelte-navigator";
import PostsPage from "./components/routes/PostsPage/PostsPage.svelte";
import HomePage from "./components/routes/HomePage/HomePage.svelte";
import BurgerMenu from 'svelte-burger-menu';
import AnimatePage from "./components/AnimatePage/AnimatePage.svelte";




</script>
<Router primary={false}>
	
<main>
	

		<Route path="/"  >
		<AnimatePage>
			<HomePage />
		</AnimatePage>
		</Route>
		<Route path="post"  >
		<AnimatePage>
			<PostsPage />
		</AnimatePage>
		</Route>
	
		
	
			

	
</main>

</Router>

<style>
	main{
margin: 0;
	}
</style>