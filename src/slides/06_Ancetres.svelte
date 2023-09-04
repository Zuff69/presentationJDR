<script>
	import { onMount } from 'svelte';
	import Slide from '../lib/Slide.svelte';
	import Code from '../lib/Code.svelte';
	import Wargame   from './07_Wargame.svelte';
	
</script>

<Slide>
	<section>
	<h2>Les ancêtres du Jeux de rôle</h2>

	<h3>Jeu Dyplomacy et le Wargame</h3>
	<div >
		<img class="img2" alt="le jeu diplomacy" src="../../assets/diplomacy.webp" />
		<img class="img2" alt="wargame a figurine" src="../../assets/wargame_fig.jpg" />
	</div>
	</section>	
	
	<section>
		<Wargame/>
	</section>
	<section>
		<img class="imageADD" alt="Chainmail" style="margin-top: -30px;" src="../../assets/chainmail.webp" />
	</section>
	
</Slide>
