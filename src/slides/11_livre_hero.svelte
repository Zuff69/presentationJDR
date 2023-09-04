<script>
	import { onMount } from 'svelte';
	import Slide from '../lib/Slide.svelte';
	import Code from '../lib/Code.svelte';

</script>

<Slide>
	<section>
		<h6>Livres dont vous êtes le héro</h6>
		<img alt="GN" src="../../assets/livre_heros.jpg" />
	</section>
	<section>
		<div class="">
			<img class="imgScUs" alt="A D D" src="../../assets/livre_1.jpg" />
			<img class="imgScUs" alt="Jeu de role des Terres du Milieu" src="../../assets/livre_2.jpg" />
			<img class="imgScUs" alt="warhammer" src="../../assets/livre_3.jpg" />
			<img class="imgScUs" alt="deadlands" src="../../assets/livre_4.jpg" />
		</div>
		<div class="">
			<img class="imgScUs" alt="James Bond" src="../../assets/livre_5.jpg" />
			<img class="imgScUs" alt="Ghostbusters" src="../../assets/livre_6.jpg" />
			<img class="imgScUs" alt="Star Wars" src="../../assets/livre_7.jpg" />
			<img class="imgScUs" alt="cobra" src="../../assets/livre_8.jpg" />
		</div>
	</section>
	<section>
		<h6 style="margin-top: -5px;">Bande Dessiné dont vous êtes le héro</h6>
		<img  class="BD" alt="BDs Jeux" src="../../assets/bd_jeux.jpg" />
	</section>
	<section>
			<h6 style="margin-top: -5px;">Les jeux dont vous êtes le héro</h6>
		<img class="img3" alt="Kriegsspiele" src="../../assets/as_as.jpg" />
		<img class="img3" alt="Wargame classique" src="../../assets/sherif.jpg" />
		<img class="img3" alt="Wargame a figurine" src="../../assets/as_dragon.jpg" />
	</section>
	<section>
		<h6 style="margin-top: -5px;">Les livres Escape-game</h6>
		<img class="img3" alt="Kriegsspiele" src="../../assets/unlock.jpg" />
		<img class="img3" alt="Wargame classique" src="../../assets/quest.jpg" />
		<img class="img3" alt="Wargame a figurine" src="../../assets/mango.jpg" />
	</section>
</Slide>
