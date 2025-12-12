<script lang="ts">
    import { Play } from 'lucide-svelte';
</script>

<section class="py-24 bg-black text-white" id="approach">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="text-center mb-20">
			<h2 class="text-4xl md:text-5xl lg:text-6xl font-serif font-normal mb-6">
				How we build<br />
				AI that works
			</h2>
			<p class="text-gray-400 text-lg max-w-2xl mx-auto">
				Custom systems shaped by real workflows, deployed fast, and fully contained within your environment.
			</p>
		</div>

		<!-- Row 1 -->
		<div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
			<!-- Card 1: Custom Builds -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[600px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Custom Builds</h3>
					<p class="text-gray-400 text-sm">Shaped by your actual workflows and institutional knowledge</p>
				</div>
                
                <!-- Mockup Content -->
                <div class="flex-1 relative">
                    <div class="absolute inset-0 flex items-center justify-center">
                         <div class="w-full h-full border border-white/5 rounded-lg bg-[#0a0a0a] p-6 font-mono text-xs text-gray-400 space-y-3">
                             <div class="text-blue-400"># Discovery Phase</div>
                             <div class="pl-4 space-y-1">
                                 <div>→ Map existing workflows</div>
                                 <div>→ Identify automation opportunities</div>
                                 <div>→ Document institutional knowledge</div>
                             </div>
                             
                             <div class="text-blue-400 mt-4"># 48-Hour Prototype</div>
                             <div class="pl-4 space-y-1">
                                 <div>→ Core workflow automation</div>
                                 <div>→ Initial model integration</div>
                                 <div class="text-green-400">✓ Working demonstration</div>
                             </div>
                             
                             <div class="text-blue-400 mt-4"># Production Build (1-3 months)</div>
                             <div class="pl-4 space-y-1">
                                 <div>→ Full system implementation</div>
                                 <div>→ Integration with existing tools</div>
                                 <div>→ Team training & handoff</div>
                             </div>
                         </div>
                    </div>
                </div>
			</div>

			<!-- Card 2: Self-Hosted Infrastructure -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[600px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Self-Hosted Infrastructure</h3>
					<p class="text-gray-400 text-sm">All data, models, and execution stay in your environment</p>
				</div>
                
                <!-- Mockup Content -->
                <div class="flex-1 relative bg-[#0a0a0a] rounded-lg border border-white/5 overflow-hidden p-6 flex flex-col">
                    <div class="space-y-4 font-mono text-[10px]">
                        <div class="bg-[#111] border border-white/5 rounded p-3">
                            <div class="text-gray-500 mb-2">DEPLOYMENT LOCATION</div>
                            <div class="text-blue-400 text-sm">Your Infrastructure</div>
                            <div class="text-gray-600 text-[9px] mt-1">On-premise or private cloud</div>
                        </div>
                        
                        <div class="bg-[#111] border border-white/5 rounded p-3">
                            <div class="text-gray-500 mb-2">DATA RESIDENCY</div>
                            <div class="text-green-400 text-sm">100% Local</div>
                            <div class="text-gray-600 text-[9px] mt-1">Never leaves your perimeter</div>
                        </div>
                        
                        <div class="bg-[#111] border border-white/5 rounded p-3">
                            <div class="text-gray-500 mb-2">TECH STACK</div>
                            <div class="text-white text-sm">Open Source</div>
                            <div class="text-gray-600 text-[9px] mt-1">8+ years battle-tested</div>
                        </div>
                        
                        <div class="bg-[#111] border border-blue-500/20 rounded p-3">
                            <div class="text-gray-500 mb-2">CONTROL LEVEL</div>
                            <div class="text-blue-400 text-sm">Full Ownership</div>
                            <div class="text-gray-600 text-[9px] mt-1">You control everything</div>
                        </div>
                    </div>
                </div>
			</div>
		</div>

        <!-- Row 2 -->
		<div class="grid grid-cols-1 md:grid-cols-3 gap-6">
			<!-- Card 3: Forward-Deployed Engineers -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Forward-Deployed Engineers</h3>
					<p class="text-gray-400 text-sm">Embedded with your team for 1-3 months</p>
				</div>
                
                 <!-- Mockup Content -->
                <div class="flex-1 relative bg-[#0a0a0a] rounded-lg border border-white/5 overflow-hidden p-4 font-mono text-[10px] leading-relaxed text-gray-400">
                    <div class="space-y-4">
                        <div class="flex items-start gap-3">
                            <div class="w-6 h-6 rounded-full bg-blue-500/20 flex items-center justify-center text-blue-400 text-[8px] shrink-0 mt-0.5">1</div>
                            <div>
                                <div class="text-white mb-1">Week 1-2: Discovery</div>
                                <div class="text-gray-500 text-[9px]">Shadow workflows, identify patterns, document requirements</div>
                            </div>
                        </div>
                        
                        <div class="flex items-start gap-3">
                            <div class="w-6 h-6 rounded-full bg-blue-500/20 flex items-center justify-center text-blue-400 text-[8px] shrink-0 mt-0.5">2</div>
                            <div>
                                <div class="text-white mb-1">Week 3-6: Build</div>
                                <div class="text-gray-500 text-[9px]">Rapid iteration with daily feedback loops</div>
                            </div>
                        </div>
                        
                        <div class="flex items-start gap-3">
                            <div class="w-6 h-6 rounded-full bg-blue-500/20 flex items-center justify-center text-blue-400 text-[8px] shrink-0 mt-0.5">3</div>
                            <div>
                                <div class="text-white mb-1">Week 7-12: Deploy</div>
                                <div class="text-gray-500 text-[9px]">Production rollout, monitoring, team training</div>
                            </div>
                        </div>
                        
                        <div class="mt-6 pt-4 border-t border-white/5">
                            <div class="text-green-400 text-[9px]">✓ Knowledge transfer complete</div>
                            <div class="text-green-400 text-[9px]">✓ System operational</div>
                            <div class="text-green-400 text-[9px]">✓ Team autonomous</div>
                        </div>
                    </div>
                </div>
			</div>

			<!-- Card 4: Platform Patterns -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Platform Patterns</h3>
					<p class="text-gray-400 text-sm">Recurring solutions become reusable infrastructure</p>
				</div>
                
                 <!-- Mockup Content -->
                <div class="flex-1 relative flex flex-col gap-3">
                    <div class="bg-[#1a1a1a] border border-white/10 rounded-lg p-4">
                        <div class="flex items-center justify-between mb-2">
                            <div class="text-xs text-white font-medium">Orchestration Layer</div>
                            <div class="text-[9px] text-blue-400">MODULAR</div>
                        </div>
                        <div class="text-[9px] text-gray-500">Workflow automation patterns extracted from custom builds</div>
                    </div>
                    
                    <div class="bg-[#1a1a1a] border border-white/10 rounded-lg p-4">
                        <div class="flex items-center justify-between mb-2">
                            <div class="text-xs text-white font-medium">Monitoring Stack</div>
                            <div class="text-[9px] text-blue-400">MODULAR</div>
                        </div>
                        <div class="text-[9px] text-gray-500">Observability tools refined across deployments</div>
                    </div>
                    
                    <div class="bg-[#1a1a1a] border border-white/10 rounded-lg p-4">
                        <div class="flex items-center justify-between mb-2">
                            <div class="text-xs text-white font-medium">Custom Workflows</div>
                            <div class="text-[9px] text-blue-400">MODULAR</div>
                        </div>
                        <div class="text-[9px] text-gray-500">Domain-specific patterns for your industry</div>
                    </div>
                    
                    <div class="mt-auto text-[9px] text-gray-600 font-mono">
                        → Improvements roll out to all clients
                    </div>
                </div>
			</div>

            <!-- Card 5: Recurring Support -->
			<div class="bg-[#0f0f0f] rounded-xl p-8 border border-white/5 h-[500px] flex flex-col relative overflow-hidden group">
				<div class="mb-8 relative z-10">
					<h3 class="text-lg font-semibold mb-1">Recurring Support</h3>
					<p class="text-gray-400 text-sm">Monthly maintenance, updates, and integration work</p>
				</div>
                
                 <!-- Mockup Content -->
                <div class="flex-1 relative flex flex-col">
                    <div class="space-y-3 flex-1">
                        <div class="bg-[#0a0a0a] rounded-lg p-4 border border-white/5">
                            <div class="flex items-center gap-2 mb-2">
                                <div class="w-2 h-2 rounded-full bg-green-400"></div>
                                <div class="text-xs text-white">System Updates</div>
                            </div>
                            <div class="text-[9px] text-gray-500">Security patches, performance improvements</div>
                        </div>
                        
                        <div class="bg-[#0a0a0a] rounded-lg p-4 border border-white/5">
                            <div class="flex items-center gap-2 mb-2">
                                <div class="w-2 h-2 rounded-full bg-green-400"></div>
                                <div class="text-xs text-white">New Integrations</div>
                            </div>
                            <div class="text-[9px] text-gray-500">Connect additional tools as needs evolve</div>
                        </div>
                        
                        <div class="bg-[#0a0a0a] rounded-lg p-4 border border-white/5">
                            <div class="flex items-center gap-2 mb-2">
                                <div class="w-2 h-2 rounded-full bg-green-400"></div>
                                <div class="text-xs text-white">Workflow Refinement</div>
                            </div>
                            <div class="text-[9px] text-gray-500">Continuous optimization based on usage</div>
                        </div>
                    </div>
                    
                    <div class="mt-4 pt-4 border-t border-white/5 text-[9px] text-gray-600 font-mono">
                        Monthly retainer • Predictable costs
                    </div>
                </div>
			</div>
		</div>
	</div>
</section>
