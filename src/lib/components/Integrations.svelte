<script lang="ts">
    const infrastructure = [
        { name: 'Docker', icon: '🐳' },
        { name: 'Kubernetes', icon: '☸️' },
        { name: 'PostgreSQL', icon: '🐘' },
        { name: 'Redis', icon: '📦' },
        { name: 'Nginx', icon: '🔧' },
        { name: 'Python', icon: '🐍' },
        { name: 'TypeScript', icon: '📘' },
        { name: 'Prometheus', icon: '📊' },
        { name: 'Grafana', icon: '📈' },
        { name: 'Elasticsearch', icon: '🔍' },
        { name: 'RabbitMQ', icon: '🐰' },
        { name: 'Terraform', icon: '🏗️' },
        { name: 'Ansible', icon: '⚙️' },
        { name: 'GitLab', icon: '🦊' },
        { name: 'Vector DB', icon: '🗄️' },
        { name: 'LangChain', icon: '🔗' }
    ];

    const security = [
        'Zero data exfiltration', 'Self-hosted models', 'Air-gapped deployment', 'Full audit logs', 
        'SOC 2 compliant', 'GDPR ready', 'HIPAA capable', 'End-to-end encryption', 
        'Role-based access', 'Network isolation', 'On-premise deployment', 'Custom compliance'
    ];
</script>

<section class="py-24 bg-black text-white" id="security">
	<div class="max-w-[1400px] mx-auto px-6 text-center">
		<h2 class="text-4xl md:text-5xl lg:text-6xl font-serif font-normal mb-6">
			Open-source stack<br />
			battle-tested infrastructure
		</h2>
		<p class="text-gray-400 text-lg max-w-2xl mx-auto mb-20">
			Built on proven technologies, hardened over 8+ years, deployed entirely within your environment.
		</p>

		<div class="grid grid-cols-1 lg:grid-cols-2 gap-20">
            <!-- Infrastructure Stack -->
			<div>
                <div class="inline-block bg-[#3b82f6] text-white text-[10px] font-bold px-3 py-1 rounded-full mb-8 tracking-wide uppercase">
                    Open-source infrastructure
                </div>
                
                <div class="grid grid-cols-4 gap-4">
                    {#each infrastructure as tool}
                        <div class="aspect-square bg-[#111] rounded-xl border border-white/5 flex flex-col items-center justify-center p-2 hover:bg-[#1a1a1a] transition-colors group">
                            <div class="text-2xl mb-2 opacity-80 group-hover:opacity-100 transition-opacity">
                                {tool.icon}
                            </div> 
                            <span class="text-[10px] text-gray-400 font-medium text-center">{tool.name}</span>
                        </div>
                    {/each}
                </div>
            </div>

            <!-- Security & Compliance -->
			<div>
                <div class="inline-block bg-[#3b82f6] text-white text-[10px] font-bold px-3 py-1 rounded-full mb-8 tracking-wide uppercase">
                    Security & Compliance
                </div>
                
                <div class="grid grid-cols-4 gap-4">
                     {#each security as item}
                        <div class="aspect-square bg-[#111] rounded-xl border border-white/5 flex flex-col items-center justify-center p-2 hover:bg-[#1a1a1a] transition-colors group">
                            <div class="w-8 h-8 rounded-full border border-white/20 mb-3 flex items-center justify-center text-white/50 group-hover:text-white transition-colors">
                                <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                    <path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/>
                                </svg>
                            </div> 
                            <span class="text-[10px] text-gray-400 text-center leading-tight font-medium">{item}</span>
                        </div>
                    {/each}
                </div>
            </div>
		</div>
	</div>
</section>
