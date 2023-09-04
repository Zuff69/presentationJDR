<script>
	import { onMount } from 'svelte';
	import Slide from '../lib/Slide.svelte';
	import Code from '../lib/Code.svelte';

</script>

<Slide>
	<section>
		<h2>Jeux d'aventure</h2>
	</section>
	<section>
		<h6>Jeux d'aventure textuelle</h6>
		<img  alt="aventure textuel"  class="imageADD" src="../../assets/textuelle.png" />
	</section>
	<section>
		<h6>Jeux d'aventure graphique</h6>
		<img  alt="aventure textuel"  class="imageADD" style="width: 900px;margin-top: -10px;" src="../../assets/mysteryhouse.webp" />
	</section>
	<section>
		<h6>Jeu d'aventure en pointer-et-cliquer</h6>
		<h7 style="margin-top: -80px; line-height: 1;">(Point & Click)</h7>
		<img  alt="aventure textuel"  class="imageADD" src="../../assets/pointClick.jpg" />
		
	</section>
		<section>
		<h6 style="margin-top: -300px;">Escape game</h6>
		<div style="margin-top: -30px;">
		<img class="img2" alt="Kriegsspiele" src="../../assets/crimsonroom.png" />
		<img class="img2" alt="Wargame classique" src="../../assets/crimson-01.jpg" />
		</div>

	</section>
	<section>
		<h6>Visual novel</h6>
		<img  alt="aventure textuel"  class="imageADD" src="../../assets/visual_novel.png" />	
	</section>

</Slide>
