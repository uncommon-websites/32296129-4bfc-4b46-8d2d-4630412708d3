<script lang="ts">
    import { Check } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="grid grid-cols-1 lg:grid-cols-2 gap-20 items-center">
            <!-- Text Content -->
			<div>
				<h2 class="text-4xl md:text-5xl lg:text-6xl font-serif font-normal mb-6 leading-tight">
					Your infrastructure,<br />
					your control
				</h2>
				<p class="text-gray-400 text-lg max-w-md mb-8">
					Deploy any model—open-source or commercial—entirely within your environment. No data ever leaves your perimeter.
				</p>
				
				<div class="space-y-4">
					<div class="flex items-start gap-3">
						<div class="w-6 h-6 rounded-full bg-blue-500/20 flex items-center justify-center text-blue-400 shrink-0 mt-1">✓</div>
						<div>
							<div class="text-white font-medium mb-1">Model Flexibility</div>
							<div class="text-sm text-gray-400">Run any open-source LLM or bring your own API keys</div>
						</div>
					</div>
					
					<div class="flex items-start gap-3">
						<div class="w-6 h-6 rounded-full bg-blue-500/20 flex items-center justify-center text-blue-400 shrink-0 mt-1">✓</div>
						<div>
							<div class="text-white font-medium mb-1">Complete Ownership</div>
							<div class="text-sm text-gray-400">All models, data, and execution stay in your infrastructure</div>
						</div>
					</div>
					
					<div class="flex items-start gap-3">
						<div class="w-6 h-6 rounded-full bg-blue-500/20 flex items-center justify-center text-blue-400 shrink-0 mt-1">✓</div>
						<div>
							<div class="text-white font-medium mb-1">No Vendor Lock-in</div>
							<div class="text-sm text-gray-400">Open-source stack means you're never dependent on us</div>
						</div>
					</div>
				</div>
			</div>
			
            <!-- Infrastructure Diagram -->
			<div class="bg-[#0f0f0f] rounded-xl p-12 border border-white/5 relative overflow-hidden h-[600px] flex items-center justify-center">
                <div class="w-full space-y-6">
					<div class="text-center mb-8">
						<div class="text-sm text-gray-500 mb-2">YOUR INFRASTRUCTURE</div>
						<div class="text-xs text-blue-400 font-mono">100% Self-Hosted</div>
					</div>
					
					<div class="space-y-4">
						<div class="bg-[#1a1a1a] border border-blue-500/30 rounded-lg p-6">
							<div class="flex items-center justify-between mb-3">
								<div class="text-white font-medium">Application Layer</div>
								<div class="w-2 h-2 rounded-full bg-green-400"></div>
							</div>
							<div class="text-xs text-gray-500 font-mono">Custom workflows • Orchestration • APIs</div>
						</div>
						
						<div class="bg-[#1a1a1a] border border-blue-500/30 rounded-lg p-6">
							<div class="flex items-center justify-between mb-3">
								<div class="text-white font-medium">Model Layer</div>
								<div class="w-2 h-2 rounded-full bg-green-400"></div>
							</div>
							<div class="text-xs text-gray-500 font-mono">Local LLMs • Vector DB • Embeddings</div>
						</div>
						
						<div class="bg-[#1a1a1a] border border-blue-500/30 rounded-lg p-6">
							<div class="flex items-center justify-between mb-3">
								<div class="text-white font-medium">Data Layer</div>
								<div class="w-2 h-2 rounded-full bg-green-400"></div>
							</div>
							<div class="text-xs text-gray-500 font-mono">PostgreSQL • Redis • Object storage</div>
						</div>
						
						<div class="bg-[#1a1a1a] border border-blue-500/30 rounded-lg p-6">
							<div class="flex items-center justify-between mb-3">
								<div class="text-white font-medium">Infrastructure Layer</div>
								<div class="w-2 h-2 rounded-full bg-green-400"></div>
							</div>
							<div class="text-xs text-gray-500 font-mono">Kubernetes • Docker • Monitoring</div>
						</div>
					</div>
					
					<div class="text-center pt-6 border-t border-white/5">
						<div class="text-xs text-gray-600 font-mono">← No external API calls</div>
						<div class="text-xs text-gray-600 font-mono">← Zero data exfiltration</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</section>
