<script>
	import { onMount } from 'svelte';
	import Slide from '../lib/Slide.svelte';
	import Code from '../lib/Code.svelte';

	import Wargame   from './07_Wargame.svelte';
</script>

<Slide>
	<section>
		<h6>Jeu de rôle Grandeur Nature (GN)</h6>
		<img alt="GN" src="../../assets/gn.jpg" />
	</section>
	<section>
		<h6>Murder Party - soirée enquête</h6>
		<img alt="MurderParty" class="imageADD" src="../../assets/murder-party.jpg" />
	</section>
	<section>
		<h6>Mascarade(tm) - Camarilla</h6>
		<img alt="Mascarade" class="imageADD" src="../../assets/masquarade.jpg" />
	</section>	
	<section>
		<img alt="killer" class="imageADD"  style="margin-top: -10px; height:700px" src="../../assets/killer.png" />
	</section>
	<section>
		<h2>Ce n'est pas du Grandeur Nature</h2>
		<div >
			<img class="img4" alt="Kriegsspiele" src="../../assets/napoleon.jpg" />
			<img class="img4" alt="Wargame classique" src="../../assets/combat.jpg" />
			<img class="img4" alt="Wargame a figurine" src="../../assets/paintball.jpg" />
			<img class="img4" alt="Wargame a figurine" src="../../assets/escape.jpg" />
		</div>
		<div >
			<div class="img4 petit_texte" >Reconstitution historique</div>
			<div class="img4 petit_texte" >Béhourd</div>
			<div class="img4 petit_texte" >Paint Ball / laser game</div>
			<div class="img4 petit_texte" >Escape Game en salle</div>
		</div>

	</section>
</Slide>
