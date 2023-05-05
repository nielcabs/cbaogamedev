<script lang="ts">
	import ContactForm from '$lib/components/ContactForm/ContactForm.svelte';
</script>

<!-- Columns -->
<div class="lg:grid grid-cols-10 gap-10 mt-10 space-y-8 lg:space-y-0">
	<!-- Portrait -->
	<div class="col-span-2 flex flex-col items-center space-y-8">
		<img
			src="/entities/npcs/npc-juniel.png"
			class="crisp bg-secondary-500 w-full max-w-[250px] aspect-square rounded-full shadow-xl"
			alt="portrait"
		/>
		<a href="https://drive.google.com/file/d/1a8cLJ15gMjKugPQcYkn1egFRHDpvvrja/view" class="inline-block btn variant-soft hover:variant-filled-primary" target="_blank">View Resume</a>
	</div>

	<!-- Bio -->
	<section class="col-span-5 space-y-4">
		<h2 class="section-header">About Juniel</h2>
		<p>
			Hi there ✌️ nice to meet you! I'm a Fullstack Developer at City College of Angeles based out of Phillipines, Pampanga.
		</p>
		<p>
			I'm an aspiring Software Engineer with a passion for writing code and making things on the web look pretty. I'm well acquainted with various Web Development & Mobile App Development as well as frontend, backend, database and blockchains. I have always been a firm believer in the human element of design and knowing your audience. Therefore, I strive to create simple, functional and impactful user experiences. I primarily code in ReactJS and JavaScript, and use Canva and Adobe XD for designing.
		</p>
		<p>
			In my free time, I love to play basketball, cook, play the online games, explore neighborhoods through food and occasionally bring out my inner photographer. Also, did someone say Shot na?
		</p>
	</section>

	<!-- Contact -->
	<section class="col-span-3 space-y-8">
		<h2 class="section-header">Reach Out</h2>
		<ContactForm />
	</section>
</div>
