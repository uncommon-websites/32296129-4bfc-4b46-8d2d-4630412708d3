<script lang="ts">
    import { Paperclip, Image, AtSign, Smile, ArrowUp } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="grid grid-cols-1 lg:grid-cols-2 gap-20 items-center">
			<div>
				<h2 class="text-4xl md:text-5xl lg:text-6xl font-serif font-normal mb-12 leading-tight">
					Built for organizations<br />
					where data stays local
				</h2>

				<div class="space-y-6">
					<div class="flex items-center gap-3 text-blue-400 font-medium">
						<div class="w-2 h-2 bg-blue-400 rounded-sm"></div>
						SME Teams
					</div>
					<p class="text-gray-400 text-sm leading-relaxed pl-5 border-l border-white/10 ml-1 mb-8">
						Where decisions rely on institutional knowledge and workflows are unique to your domain.
					</p>

					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						Public Sector & Regulated Environments
					</div>
					<p class="text-gray-400 text-sm leading-relaxed pl-5 border-l border-white/10 ml-1 mb-8 opacity-0 hover:opacity-100 transition-opacity">
						Where data cannot leave the perimeter and permissions must be auditable.
					</p>
					
					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						Research & Technical Organizations
					</div>
					<p class="text-gray-400 text-sm leading-relaxed pl-5 border-l border-white/10 ml-1 mb-8 opacity-0 hover:opacity-100 transition-opacity">
						Where expertise is deep and analysis is repeated.
					</p>
					
					<div class="flex items-center gap-3 text-gray-500 hover:text-white transition-colors cursor-pointer">
						<div class="w-2 h-2 bg-gray-500 rounded-sm"></div>
						Infrastructure & Service Providers
					</div>
					<p class="text-gray-400 text-sm leading-relaxed pl-5 border-l border-white/10 ml-1 mb-8 opacity-0 hover:opacity-100 transition-opacity">
						Where internal tooling must be private and aligned to real operations.
					</p>
				</div>
			</div>

			<div class="relative">
                <div class="rounded-xl overflow-hidden aspect-square relative bg-[#0a0a0a] border border-white/10">
                     <!-- Terminal-style visualization -->
                     <div class="w-full h-full p-8 font-mono text-xs flex flex-col justify-center">
                         <div class="space-y-6">
                             <div class="space-y-2">
                                 <div class="text-gray-500">$ greyhaven status</div>
                                 <div class="text-blue-400">→ Deployment: Self-hosted</div>
                                 <div class="text-blue-400">→ Data location: Client infrastructure</div>
                                 <div class="text-green-400">→ Status: Operational</div>
                             </div>
                             
                             <div class="space-y-2 pt-4 border-t border-white/5">
                                 <div class="text-gray-500"># Security posture</div>
                                 <div class="text-gray-400">✓ Zero data exfiltration</div>
                                 <div class="text-gray-400">✓ Audit logs enabled</div>
                                 <div class="text-gray-400">✓ Compliance maintained</div>
                             </div>
                             
                             <div class="space-y-2 pt-4 border-t border-white/5">
                                 <div class="text-gray-500"># Integration status</div>
                                 <div class="text-gray-400">→ Custom workflows: <span class="text-green-400">Active</span></div>
                                 <div class="text-gray-400">→ Local models: <span class="text-green-400">Running</span></div>
                                 <div class="text-gray-400">→ Monitoring: <span class="text-green-400">Enabled</span></div>
                             </div>
                         </div>
                     </div>
                </div>
			</div>
		</div>
	</div>
</section>
