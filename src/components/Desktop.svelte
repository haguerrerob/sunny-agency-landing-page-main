<script>
	import Header from '../components/Header.svelte';
</script>

<div class="relative  hidden sm:flex flex-col w-full mx-auto justify-center bg-white">
	<Header />
	<img src="/images/desktop/image-header.jpg" alt="header" />

	<div class="flex">
		<div class="flex flex-col w-1/2 justify-center items-start px-10">
			<h1 class="font-Fraunces font-black text-4xl lg:text-6xl mx-5 my-5">Transform your brand</h1>
			<p class="font-Barlow text-slate-500 text-lg sm:text-xs md:text-sm lg:text-md mx-4">
				We are a full-service creative agency specializing in helping brands grow fast. Engage your
				clients throught compelling visual that do most of the marketing for you.
			</p>
			<button
				class="self-star font-Fraunces font-black text-lg mx-5 my-5 hover:underline-offset-4 underline decoration-[#ffd602]"
				>LEARN MORE
			</button>
		</div>

		<img class="w-1/2" src="/images/desktop/image-transform.jpg" alt="transform" />
	</div>

	<div class="flex">
		<img class="w-1/2" src="/images/desktop/image-stand-out.jpg" alt="stand" />
		<div class="flex flex-col w-1/2 justify-center items-start px-10">
			<h1 class="font-Fraunces font-black text-4xl lg:text-6xl mx-8 my-5">
				Stand out to the right audience
			</h1>
			<p class="font-Barlow text-slate-500 text-lg sm:text-xs md:text-sm lg:text-md mx-6">
				Using a collaborative formula of designers, researchers, photographers, videographers, and
				copywriters, we'll build and extend your brand in digital places.
			</p>
			<button
				class="font-Fraunces font-black text-lg mx-5 my-5 text-center hover:underline-offset-4 underline decoration-[#fe6f61]"
				>LEARN MORE</button
			>
		</div>
	</div>

	<div class="flex">
		<div class="w-1/2 relative">
			<img class="w-full" src="/images/desktop/image-graphic-design.jpg" alt="design" />
			<div class="absolute top-1/2 flex flex-col items-center">
				<h1 class="font-Fraunces text-[#25564B] font-black text-md lg:text-2xl my-5">
					Graphic Design
				</h1>
				<p
					class="font-Barlow text-[#25564B] text-[10px] md:text-sm lg:text-md mx-5 text-center w-2/3 mb-16"
				>
					Great design makes you memorable. We deliver artwork that underscores your brand message
					and captures potential clients´ attention.
				</p>
			</div>
		</div>
		<div class="w-1/2 relative">
			<img class="w-full" src="/images/desktop/image-photography.jpg" alt="photography" />
			<div class="absolute top-1/2 flex flex-col items-center">
				<h1 class="font-Fraunces text-[#19536B] font-black text-md lg:text-2xl my-5">
					Photography
				</h1>
				<p
					class="text-[#19536B] font-Barlow text-[10px] md:text-sm lg:text-md mx-5 text-center w-2/3 mb-16"
				>
					Increase your credibility by getting the most stunning, high-quality photos that improve
					your business image.
				</p>
			</div>
		</div>
	</div>
	<div class="my-20 self-center">
		<h1
			class="font-Fraunces text-slate-500 tracking-widest font-black text-xl lg:text-2xl text-center"
		>
			CLIENT TESTIMONIALS
		</h1>
		<div class="flex justify-around">
			<div class=" mt-2">
				<div class="container mx-auto w-1/5">
					<img class="my-5 rounded-full" src="/images/image-emily.jpg" alt="emily" />
				</div>
				<p
					class="font-Barlow text-slate-500 text-md sm:text-[10px] md:text-xs lg:text-sm mx-5 mb-5 text-center"
				>
					We put our trust in Sunnyside and they delivered, making sure our needs were met and
					deadlines were always hit.
				</p>
				<p class="font-Fraunces font-black text-xl sm:text-sm lg:text-md text-center">Emily R.</p>
				<p class="font-Barlow text-slate-400 text-center sm:text-[10px] lg:text-sm">
					Marketing Director
				</p>
			</div>

			<div class=" mt-2">
				<div class="container mx-auto w-1/6">
					<img class="mt-5 mb-6 rounded-full" src="/images/image-thomas.jpg" alt="thomas" />
				</div>
				<p
					class="font-Barlow text-slate-500 text-md sm:text-[10px] md:text-xs lg:text-sm mx-5 mb-5 text-center"
				>
					Sunnyside´s enthusiasm coupled with their keen interest in our brand´s success made it a
					satisfying and enjoyable experience.
				</p>
				<p class="font-Fraunces font-black text-xl sm:text-sm lg:text-md text-center">Thomas S.</p>
				<p class="font-Barlow text-slate-400 text-center sm:text-[10px] lg:text-sm">
					Chief Operating Officer
				</p>
			</div>

			<div class=" mt-2">
				<div class="container mx-auto w-1/5">
					<img class="my-5 rounded-full" src="/images/image-jennie.jpg" alt="jennie" />
				</div>
				<p
					class="font-Barlow text-slate-500 text-md sm:text-[10px] md:text-xs lg:text-sm mx-5 mb-5 text-center"
				>
					Incredible end result! Our sales increased over 400% when we worked with Sunnyside. Highly
					recommended!
				</p>
				<p class="font-Fraunces font-black text-xl sm:text-sm lg:text-md text-center">Jennie F.</p>
				<p class="font-Barlow text-slate-400 text-center sm:text-[10px] lg:text-sm">
					Business Owner
				</p>
			</div>
		</div>
	</div>
	<div class="flex">
		<img class="w-1/4" src="/images/desktop/image-gallery-milkbottles.jpg" alt="img" />
		<img class="w-1/4" src="/images/desktop/image-gallery-orange.jpg" alt="img" />
		<img class="w-1/4" src="/images/desktop/image-gallery-cone.jpg" alt="img" />
		<img class="w-1/4" src="/images/desktop/image-gallery-sugarcubes.jpg" alt="img" />
	</div>
	<div class="flex mx-auto w-full bg-[#9ddbcc]">
		<div class="flex flex-col items-center w-full my-16">
			<h1 class=" text-[#22443D] mb-5 text-5xl text-center">sunnyside</h1>
			<div
				class=" container w-1/2 flex flex-row justify-around my-5 font-Barlow text-[#22443D] text-lg"
			>
				<div class="">About</div>
				<div>Service</div>
				<div>Projects</div>
			</div>
			<div class=" container w-1/2 flex flex-row justify-around my-10">
				<img src="/images/icon-facebook.svg" alt="facebook" />
				<img src="/images/icon-instagram.svg" alt="instagram" />
				<img src="/images/icon-twitter.svg" alt="twitter" />
				<img src="/images/icon-pinterest.svg" alt="pinterest" />
			</div>
		</div>
	</div>
</div>
