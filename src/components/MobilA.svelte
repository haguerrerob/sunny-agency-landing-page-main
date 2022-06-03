<script>
	import Header from '../components/Header.svelte';

	let band = false;
</script>

<div class="container mx-auto flex flex-col items-center justify-center bg-white sm:hidden">
	<div class="container mx-auto relative flex items-center">
		<Header on:click={() => (band = !band)} />
		<img class="w-full" src="/images/mobile/image-header.jpg" alt="header" />
		<div class="container flex flex-col absolute top-1/4 self-center">
			<h1 class="font-Fraunces font-black self-center text-5xl text-white text-center">WE ARE</h1>
			<h1 class="font-Fraunces font-black self-center text-5xl text-white text-center">
				CREATIVES
			</h1>
			<img class="self-center mt-10" src="/images/icon-arrow-down.svg " alt="arrow" />
		</div>
		{#if band}
			<div on:mouseleave={() => (band = !band)}>
				<div
					class="container absolute top-28 w-4/5 flex justify-end left-0 right-0 m-auto md:hidden"
				>
					<div
						class="w-0 h-0 right-0 border-l-transparent border-l-[10px] border-t-transparent border-t-[10px] border-b-white border-b-[10px] border-r-white border-r-[10px]"
					/>
				</div>
				<div
					class="container md:hidden w-4/5 h-1/2 absolute bg-white  left-0 right-0 top-32 m-auto flex flex-col justify-center items-center font-Barlow text-slate-500 "
				>
					<div class="flex flex-col">
						<button
							class="border-solid rounded-full hover:bg-amber-400 hover:font-black hover:text-black px-8 py-3"
							>About</button
						>
						<button
							class="border-solid rounded-full hover:bg-amber-400 hover:font-black hover:text-black px-8 py-3"
							>Services</button
						>
						<button
							class="border-solid rounded-full hover:bg-amber-400 hover:font-black hover:text-black px-8 py-3"
							>Projects</button
						>
						<button
							class="border-solid rounded-full hover:bg-amber-400 hover:font-black hover:text-black px-8 py-3"
							>CONTACT</button
						>
					</div>
				</div>
			</div>
		{/if}
	</div>

	<img class="w-full" src="/images/mobile/image-transform.jpg" alt="transform" />

	<div class="container flex flex-col items-center">
		<h1 class="font-Fraunces font-black text-4xl sm:text-6xl mx-5 my-5 text-center">
			Transform your brand
		</h1>
		<p class="font-Barlow text-slate-500 text-lg sm:text-xl mx-4 text-center">
			We are a full-service creative agency specializing in helping brands grow fast. Engage your
			clients throught compelling visual that do most of the marketing for you.
		</p>
		<button
			class="font-Fraunces font-black text-lg sm:text-xl mx-5 my-5 text-center hover:underline-offset-4 underline decoration-[#ffd602]"
			>LEARN MORE</button
		>
	</div>

	<img class="w-full" src="/images/mobile/image-stand-out.jpg" alt="stand" />

	<div class="container flex flex-col items-center my-10">
		<h1 class="font-Fraunces font-black text-4xl sm:text-6xl mx-8 my-5 text-center">
			Stand out to the right audience
		</h1>
		<p class="font-Barlow text-slate-500 text-lg sm:text-xl mx-6 text-center">
			Using a collaborative formula of designers, researchers, photographers, videographers, and
			copywriters, we'll build and extend your brand in digital places.
		</p>
		<button
			class="font-Fraunces font-black text-lg sm:text-xl mx-5 my-5 text-center hover:underline-offset-4 underline decoration-[#fe6f61]"
			>LEARN MORE</button
		>
	</div>
	<div class="container mx-auto relative">
		<img class="w-full" src="/images/mobile/image-graphic-design.jpg" alt="design" />
		<div class="container absolute top-2/3 flex flex-col items-center">
			<h1 class="font-Fraunces text-[#25564B] font-black text-4xl sm:text-6xl my-5">
				Graphic Design
			</h1>
			<p class="font-Barlow text-[#25564B] text-md sm:text-lg mx-5 text-center">
				Great design makes you memorable. We deliver artwork that underscores your brand message and
				captures potential clients´ attention.
			</p>
		</div>
	</div>
	<div class="container mx-auto relative">
		<img class="w-full" src="/images/mobile/image-photography.jpg" alt="photography" />
		<div class="container absolute top-2/3 flex flex-col items-center">
			<h1 class="font-Fraunces text-[#19536B] font-black text-4xl sm:text-6xl mb-10">
				Photography
			</h1>
			<p class="text-[#19536B] font-Barlow text-md sm:text-xl mx-5 text-center">
				Increase your credibility by getting the most stunning, high-quality photos that improve
				your business image.
			</p>
		</div>
	</div>

	<div class="container mx-auto flex flex-col items-center my-16">
		<h1 class="font-Fraunces text-slate-500 tracking-widest font-black text-xl">
			CLIENT TESTIMONIALS
		</h1>
		<div class=" mt-16">
			<div class="container mx-auto w-1/5">
				<img class="my-5 rounded-full" src="/images/image-emily.jpg" alt="emily" />
			</div>
			<p class="font-Barlow text-slate-500 text-md sm:text-xl mx-10 mb-5 text-center">
				We put our trust in Sunnyside and they delivered, making sure our needs were met and
				deadlines were always hit.
			</p>
			<p class="font-Fraunces font-black text-xl text-center">Emily R.</p>
			<p class="font-Barlow text-slate-500 text-center">Marketing Director</p>
		</div>

		<div class=" mt-16">
			<div class="container mx-auto w-1/5">
				<img class="my-5 rounded-full" src="/images/image-thomas.jpg" alt="thomas" />
			</div>
			<p class="font-Barlow text-slate-500 text-md sm:text-xl mx-10 mb-5 text-center">
				Sunnyside´s enthusiasm coupled with their keen interest in our brand´s success made it a
				satisfying and enjoyable experience.
			</p>
			<p class="font-Fraunces font-black text-xl text-center">Thomas S.</p>
			<p class="font-Barlow text-slate-400 text-center">Chief Operating Officer</p>
		</div>

		<div class=" mt-16">
			<div class="container mx-auto w-1/5">
				<img class="my-5 rounded-full" src="/images/image-jennie.jpg" alt="jennie" />
			</div>
			<p class="font-Barlow text-slate-500 text-md sm:text-xl mx-10 mb-5 text-center">
				Incredible end result! Our sales increased over 400% when we worked with Sunnyside. Highly
				recommended!
			</p>
			<p class="font-Fraunces font-black text-xl text-center">Jennie F.</p>
			<p class="font-Barlow text-slate-400 text-center">Business Owner</p>
		</div>
	</div>

	<div class="w-full grid grid-cols-2">
		<img class="w-full" src="/images/mobile/image-gallery-milkbottles.jpg" alt="img" />
		<img class="w-full" src="/images/mobile/image-gallery-orange.jpg" alt="img" />
		<img class="w-full" src="/images/mobile/image-gallery-cone.jpg" alt="img" />
		<img class="w-full" src="/images/mobile/image-gallery-sugar-cubes.jpg" alt="img" />
	</div>

	<div class="container mx-auto w-full bg-[#9ddbcc]">
		<div class="container mx-auto flex flex-col items-center my-16">
			<h1 class=" text-[#22443D] mb-5 text-5xl">sunnyside</h1>
			<div class=" container flex flex-row justify-around my-5 font-Barlow text-[#22443D] text-lg">
				<div class="">About</div>
				<div>Service</div>
				<div>Projects</div>
			</div>
			<div class=" container w-2/3 flex flex-row justify-around my-10">
				<img src="/images/icon-facebook.svg" alt="facebook" />
				<img src="/images/icon-instagram.svg" alt="instagram" />
				<img src="/images/icon-twitter.svg" alt="twitter" />
				<img src="/images/icon-pinterest.svg" alt="pinterest" />
			</div>
		</div>
	</div>
</div>
