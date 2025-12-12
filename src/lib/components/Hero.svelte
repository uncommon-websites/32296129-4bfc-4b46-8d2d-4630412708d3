<script lang="ts">
	import { onMount } from 'svelte';
</script>

<section class="relative pt-32 pb-20 overflow-hidden bg-black text-white">
	<div class="max-w-[1400px] mx-auto px-6">
		<div class="max-w-4xl">
			<h1 class="text-6xl md:text-7xl lg:text-[5.5rem] leading-[1.1] font-serif font-normal tracking-tight mb-8">
				Local-first AI systems<br />
				<span class="italic font-light font-serif">shaped by real work</span>
			</h1>

			<p class="text-xl text-gray-400 max-w-2xl mb-10 leading-relaxed font-light font-sans">
				Fast to deploy, fully contained, under your control. Custom AI systems that run entirely inside your environment—built from your workflows, deployed by forward-deployed engineers.
			</p>

			<div class="flex flex-wrap gap-4 mb-20">
				<button class="bg-[#3b82f6] hover:bg-blue-600 text-white px-8 py-4 rounded-full font-medium transition-colors text-base">
					Start a conversation
				</button>
				<button class="bg-white/10 hover:bg-white/20 border border-white/10 text-white px-8 py-4 rounded-full font-medium transition-colors text-base">
					View case studies
				</button>
			</div>
		</div>
	</div>

	<!-- Hero Image Container with Perspective -->
	<div class="relative w-full max-w-[1400px] mx-auto px-6 perspective-container">
		<div class="relative transform-3d hero-image-container origin-top opacity-90 hover:opacity-100 transition-opacity duration-700">
			<!-- Terminal/Infrastructure Mockup -->
			<div class="rounded-xl overflow-hidden border border-white/10 shadow-2xl bg-[#0a0a0a] aspect-[16/10] relative">
				<!-- Top bar -->
				<div class="h-10 bg-[#111] border-b border-white/5 flex items-center px-4 gap-2">
                    <div class="flex gap-2">
                        <div class="w-3 h-3 rounded-full bg-red-500/20"></div>
                        <div class="w-3 h-3 rounded-full bg-yellow-500/20"></div>
                        <div class="w-3 h-3 rounded-full bg-green-500/20"></div>
                    </div>
                    <div class="mx-auto w-1/3 h-6 bg-white/5 rounded-md text-[10px] flex items-center justify-center text-gray-500 font-mono">
                        localhost:8080
                    </div>
				</div>
				<!-- Terminal Content -->
				<div class="flex h-full">
                    <!-- Sidebar -->
                    <div class="w-64 border-r border-white/5 bg-[#0f0f0f] p-4 hidden md:block">
                        <div class="space-y-3">
                            <div class="text-[10px] text-gray-500 font-mono mb-4">PROJECT STRUCTURE</div>
                            <div class="flex items-center gap-2 text-[10px] text-gray-400 font-mono">
                                <span class="text-blue-400">📁</span> /orchestration
                            </div>
                            <div class="flex items-center gap-2 text-[10px] text-gray-400 font-mono pl-3">
                                <span class="text-green-400">📄</span> workflow.py
                            </div>
                            <div class="flex items-center gap-2 text-[10px] text-gray-400 font-mono">
                                <span class="text-blue-400">📁</span> /models
                            </div>
                            <div class="flex items-center gap-2 text-[10px] text-gray-400 font-mono pl-3">
                                <span class="text-green-400">📄</span> local_llm.py
                            </div>
                            <div class="flex items-center gap-2 text-[10px] text-gray-400 font-mono">
                                <span class="text-blue-400">📁</span> /monitoring
                            </div>
                            <div class="flex items-center gap-2 text-[10px] text-gray-400 font-mono">
                                <span class="text-green-400">📄</span> docker-compose.yml
                            </div>
                        </div>
                    </div>
                    <!-- Main Terminal -->
                    <div class="flex-1 p-6 bg-[#0a0a0a] font-mono text-[11px] leading-relaxed">
                        <div class="text-green-400 mb-4">$ greyhaven deploy --env production</div>
                        <div class="text-gray-500 space-y-1">
                            <div>→ Initializing self-hosted infrastructure...</div>
                            <div>→ Loading custom workflow models...</div>
                            <div class="text-blue-400">✓ Local LLM deployed (client environment)</div>
                            <div class="text-blue-400">✓ Orchestration layer active</div>
                            <div class="text-blue-400">✓ Monitoring stack running</div>
                            <div class="text-green-400 mt-4">✓ System operational - all data local</div>
                        </div>
                        
                        <div class="mt-8 grid grid-cols-3 gap-4">
                            <div class="bg-[#111] p-3 rounded border border-white/5">
                                <div class="text-[9px] text-gray-500 mb-1">LATENCY</div>
                                <div class="text-green-400 text-lg">24ms</div>
                            </div>
                            <div class="bg-[#111] p-3 rounded border border-white/5">
                                <div class="text-[9px] text-gray-500 mb-1">UPTIME</div>
                                <div class="text-green-400 text-lg">99.9%</div>
                            </div>
                            <div class="bg-[#111] p-3 rounded border border-white/5">
                                <div class="text-[9px] text-gray-500 mb-1">DATA LOCATION</div>
                                <div class="text-blue-400 text-lg">LOCAL</div>
                            </div>
                        </div>

                        <div class="mt-6 bg-[#111] rounded border border-white/5 p-4">
                            <div class="text-[9px] text-gray-500 mb-2">SYSTEM STATUS</div>
                            <div class="space-y-2">
                                <div class="flex items-center justify-between text-[10px]">
                                    <span class="text-gray-400">Custom workflow engine</span>
                                    <span class="text-green-400">● ACTIVE</span>
                                </div>
                                <div class="flex items-center justify-between text-[10px]">
                                    <span class="text-gray-400">Open-source stack</span>
                                    <span class="text-green-400">● ACTIVE</span>
                                </div>
                                <div class="flex items-center justify-between text-[10px]">
                                    <span class="text-gray-400">Client-controlled deployment</span>
                                    <span class="text-green-400">● ACTIVE</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

				<!-- Gradient Overlay -->
				<div class="absolute inset-0 bg-gradient-to-t from-black/40 via-transparent to-transparent pointer-events-none"></div>
			</div>
		</div>
	</div>
    
    <!-- Industry Focus -->
    <div class="max-w-[1400px] mx-auto px-6 mt-20">
        <p class="text-center text-sm text-gray-500 mb-6 uppercase tracking-wider">Built for data-sensitive environments</p>
        <div class="flex flex-wrap justify-center items-center gap-8 md:gap-12 opacity-60">
            <span class="text-base font-medium font-sans text-gray-400">Public Sector</span>
            <span class="text-base font-medium font-sans text-gray-400">Healthcare</span>
            <span class="text-base font-medium font-sans text-gray-400">Legal</span>
            <span class="text-base font-medium font-sans text-gray-400">Defense</span>
            <span class="text-base font-medium font-sans text-gray-400">Research</span>
            <span class="text-base font-medium font-sans text-gray-400">Infrastructure</span>
        </div>
    </div>
</section>

<style>
	.perspective-container {
		perspective: 2000px;
	}
	.transform-3d {
		transform: rotateX(20deg) scale(0.9);
        transform-style: preserve-3d;
	}
</style>
