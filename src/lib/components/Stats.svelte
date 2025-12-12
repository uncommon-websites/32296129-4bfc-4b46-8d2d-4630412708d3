<script lang="ts">
	import { ArrowLeft, ArrowRight } from 'lucide-svelte';
</script>

<section class="py-20 bg-black text-white border-t border-white/5">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 lg:gap-12">
			<!-- Stat 1 -->
			<div class="flex flex-col h-full justify-between group cursor-pointer">
				<p class="text-sm text-gray-400 mb-8 leading-relaxed">
					From initial conversation to working prototype
				</p>
				<div>
					<div class="text-5xl md:text-6xl font-normal mb-2 tracking-tight">48h</div>
					<div class="flex items-center gap-2">
						<div class="w-2 h-2 rounded-full bg-blue-500"></div>
						<span class="text-xs font-semibold tracking-wider text-gray-400 uppercase">Prototype Delivery</span>
					</div>
				</div>
			</div>

			<!-- Stat 2 -->
			<div class="flex flex-col h-full justify-between group cursor-pointer">
				<p class="text-sm text-gray-400 mb-8 leading-relaxed">
					All data, models, and execution stay within your infrastructure
				</p>
				<div>
					<div class="text-5xl md:text-6xl font-normal mb-2 tracking-tight">100%</div>
					<div class="flex items-center gap-2">
						<div class="w-2 h-2 rounded-full bg-blue-500"></div>
						<span class="text-xs font-semibold tracking-wider text-gray-400 uppercase">Data Sovereignty</span>
					</div>
				</div>
			</div>

			<!-- Stat 3 -->
			<div class="flex flex-col h-full justify-between group cursor-pointer">
				<p class="text-sm text-gray-400 mb-8 leading-relaxed">
					Open-source stack hardened over years of production use
				</p>
				<div>
					<div class="text-5xl md:text-6xl font-normal mb-2 tracking-tight">8+</div>
					<div class="flex items-center gap-2">
						<div class="w-2 h-2 rounded-full bg-blue-500"></div>
						<span class="text-xs font-semibold tracking-wider text-gray-400 uppercase">Years Battle-Tested</span>
					</div>
				</div>
			</div>

			<!-- Stat 4 -->
			<div class="flex flex-col h-full justify-between group cursor-pointer">
				<p class="text-sm text-gray-400 mb-8 leading-relaxed">
					Forward-deployed engineers embedded with your team
				</p>
				<div>
					<div class="text-5xl md:text-6xl font-normal mb-2 tracking-tight">1-3</div>
					<div class="flex items-center gap-2">
						<div class="w-2 h-2 rounded-full bg-blue-500"></div>
						<span class="text-xs font-semibold tracking-wider text-gray-400 uppercase">Months to Production</span>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>
