<script lang="ts">
    import { Check } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white border-t border-white/5" id="services">
	<div class="max-w-[1400px] mx-auto px-6">
		<h2 class="text-4xl font-serif font-normal mb-6">Service Model</h2>
		<p class="text-gray-400 mb-16 max-w-2xl">Transparent pricing that scales with your needs—from initial prototype to ongoing support.</p>

		<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
			<!-- Setup Fee -->
			<div class="border-r border-white/10 pr-8">
				<h3 class="text-xl font-bold mb-2">Setup Fee</h3>
				<p class="text-blue-400 text-sm mb-6">One-time</p>
				<button class="bg-white text-black px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-gray-200 transition-colors">
					Get started
				</button>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">INITIAL DEPLOYMENT</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-blue-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Self-hosted infrastructure setup</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-blue-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Open-source stack deployment</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-blue-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Initial security configuration</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-blue-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Environment provisioning</span>
					</li>
				</ul>
			</div>

			<!-- FDE Builds -->
			<div class="border-r border-white/10 pr-8">
				<h3 class="text-xl font-bold mb-2">FDE Builds</h3>
				<p class="text-blue-400 text-sm mb-6">1-3 months</p>
				<button class="bg-transparent border border-white/20 text-white px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-white/10 transition-colors">
					Learn more
				</button>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">CUSTOM BUILD PHASE</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-blue-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>48-hour prototype delivery</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-blue-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Forward-deployed engineers</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-blue-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Custom workflow integration</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-blue-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Production deployment</span>
					</li>
                     <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-blue-500 flex items-center justify-center text-white text-[8px] font-bold mt-0.5">✓</div>
						<span>Team training & handoff</span>
					</li>
				</ul>
			</div>

			<!-- Free -->
			<div>
				<h3 class="text-xl font-bold mb-2">Free</h3>
				<p class="text-pink-500 text-sm mb-6">$0</p>
				<button class="bg-transparent border border-white/20 text-white px-6 py-2 rounded-full text-sm font-bold mb-12 hover:bg-white/10 transition-colors">
					Try it free
				</button>

                <div class="mb-4 text-[10px] font-bold text-gray-500 uppercase tracking-wider">IDEAL FOR INDIVIDUALS</div>
				<ul class="space-y-4">
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-pink-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>10 meetings per month — invite members for more</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-pink-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Up to 5 members per workspace</span>
					</li>
					<li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-pink-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Unlimited assistants and prompt templates</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-pink-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Meeting integrations with Calendar, Drive, Meet, Teams, and Zoom</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-pink-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Data integrations with Confluence, Google Drive, OneDrive, Notion, and Sharepoint</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-pink-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>1000 documents per integration</span>
					</li>
                    <li class="flex items-start gap-3 text-sm text-gray-300">
						<div class="w-4 h-4 rounded-full bg-pink-500 flex items-center justify-center text-black text-[8px] font-bold mt-0.5">✓</div>
						<span>Help center support</span>
					</li>
				</ul>
			</div>
		</div>
	</div>
</section>
