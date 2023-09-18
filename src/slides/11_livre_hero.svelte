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
		<h6 style="margin-top: -15px; margin-bottom: 0px;">Bande Dessinée dont vous êtes le héro</h6>
		<div>
			<img class="img3L" alt="" src="../../assets/pif.jpg" />
			<img class="img3L" alt="" src="../../assets/mickey.jpg" />
			<img class="img3L" alt="" src="../../assets/asterix.jpg" />
		</div>
		<div >
			<img class="img3L"   alt="" src="../../assets/astrapi.jpg" />
			<img class="img3L"   alt="" src="../../assets/Deadpool.jpg" />
			<img class="img3L"   alt="" src="../../assets/ebene.jpg" />	
		</div>	

	</section>
	<section>
		<h6 style="margin-top: -15px; margin-bottom: 0px;">Les jeux dont vous êtes le héro</h6>

		<div>
			<img class="img3L" alt="Kriegsspiele" src="../../assets/as_as.jpg" />
			<img class="img3L" alt="Wargame classique" src="../../assets/sherif.jpg" />
			<img class="img3L" alt="Wargame a figurine" src="../../assets/lost_worlds.jpg" />
		</div>
		<div >
			<img class="img3L"   alt="" src="../../assets/nuit.jpg" />
			<img class="img3L"   alt="" src="../../assets/sherlock.jpg" />
			<img class="img3L"   alt="" src="../../assets/cartaventura.jpg" />	
		</div>	
	</section>
	<section>
		<h6 style="margin-top: -5px;">Les livres Escape-game</h6>
		<img class="img3" alt="Kriegsspiele" src="../../assets/unlock.jpg" />
		<img class="img3" alt="Wargame classique" src="../../assets/quest.jpg" />
		<img class="img3" alt="Wargame a figurine" src="../../assets/mango.jpg" />
	</section>
</Slide>
