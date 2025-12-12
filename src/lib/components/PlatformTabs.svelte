<script>
    // No script logic needed for this static recreation yet
</script>

<section class="py-20 bg-white font-sans">
    <div class="max-w-7xl mx-auto px-4 text-center">
        <span class="text-[10px] font-bold text-gray-500 uppercase tracking-widest border border-gray-200 px-3 py-1.5 rounded-full bg-gray-50">Meet the AirOps Platform</span>
        <h2 class="mt-8 text-5xl md:text-7xl font-serif-display text-gray-900 leading-tight">Where great <br/> brands go to drive <br/> growth</h2>
    </div>
    
    <!-- Tabbed interface image area -->
    <div class="max-w-7xl mx-auto mt-16 px-4">
        <div class="border border-gray-200 rounded-xl overflow-hidden shadow-sm bg-white grid md:grid-cols-12 min-h-[600px]">
             <div class="md:col-span-4 p-8 md:p-12 border-r border-gray-200 flex flex-col justify-center">
                 <h3 class="text-3xl font-serif-display mb-4">The smartest move is knowing your next</h3>
                 <p class="text-gray-600 text-base leading-relaxed mb-8">In this new era, you need to know what to create to win visitors and customers. The AirOps platform brings together your data, competitors, and audience behavior so you can create a winning SEO content strategy with ease. Filter and view action items by URL, topic, and ease of effort, giving you a clear path.</p>
                 <div>
                    <button class="text-sm font-bold border-b border-gray-300 pb-0.5 hover:border-gray-900 transition-colors">Learn More -></button>
                 </div>
             </div>
             <div class="md:col-span-8 bg-gray-50 p-8 md:p-12 flex items-center justify-center relative overflow-hidden">
                 <!-- Simplified UI Mockup -->
                 <div class="bg-white shadow-xl rounded-lg w-full h-full border border-gray-200 p-6 relative flex flex-col">
                    <div class="flex gap-2 mb-6 border-b border-gray-100 pb-4">
                        <div class="w-3 h-3 rounded-full bg-red-400"></div>
                        <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
                        <div class="w-3 h-3 rounded-full bg-green-400"></div>
                        <div class="ml-auto flex gap-2">
                            <div class="h-4 w-32 bg-gray-100 rounded-full"></div>
                        </div>
                    </div>
                    
                    <div class="space-y-6">
                        <!-- Header Stats -->
                        <div class="grid grid-cols-4 gap-4">
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Keywords</div>
                                 <div class="text-xl font-bold text-gray-900">1,240</div>
                                 <div class="text-[10px] text-green-600 font-bold">+12%</div>
                             </div>
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Traffic</div>
                                 <div class="text-xl font-bold text-gray-900">45.2k</div>
                                 <div class="text-[10px] text-green-600 font-bold">+8.5%</div>
                             </div>
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Value</div>
                                 <div class="text-xl font-bold text-gray-900">$12.4k</div>
                                 <div class="text-[10px] text-green-600 font-bold">+3.2%</div>
                             </div>
                             <div class="p-3 bg-gray-50 rounded border border-gray-100">
                                 <div class="text-[10px] text-gray-500 uppercase font-bold">Difficulty</div>
                                 <div class="text-xl font-bold text-gray-900">42</div>
                                 <div class="text-[10px] text-gray-400 font-bold">Avg</div>
                             </div>
                        </div>

                        <!-- Data Table -->
                        <div class="border border-gray-100 rounded-lg overflow-hidden">
                            <div class="bg-gray-50 px-4 py-2 border-b border-gray-100 flex text-[10px] font-bold text-gray-500 uppercase tracking-wider">
                                <div class="w-1/3">Keyword</div>
                                <div class="w-1/6 text-right">Vol</div>
                                <div class="w-1/6 text-right">KD</div>
                                <div class="w-1/6 text-right">CPC</div>
                                <div class="w-1/6 text-right">Status</div>
                            </div>
                            <div class="divide-y divide-gray-50 text-xs">
                                 {#each [
                                     {creative: 'Tech News - Contextual', imp: '124k', ctr: '4.2%', conv: '3.8%', status: 'Active'},
                                     {creative: 'Finance - Dynamic CTA', imp: '98k', ctr: '3.9%', conv: '3.2%', status: 'Active'},
                                     {creative: 'Lifestyle - Personalized', imp: '87k', ctr: '3.5%', conv: '2.9%', status: 'Active'},
                                     {creative: 'Sports - Real-time', imp: '76k', ctr: '4.1%', conv: '3.5%', status: 'Learning'},
                                     {creative: 'Travel - Seasonal', imp: '65k', ctr: '3.7%', conv: '3.1%', status: 'Testing'}
                                 ] as item}
                                 <div class="px-4 py-3 flex items-center hover:bg-gray-50 transition-colors">
                                     <div class="w-1/3 font-medium text-gray-900">{item.creative}</div>
                                     <div class="w-1/6 text-right text-gray-600">{item.imp}</div>
                                     <div class="w-1/6 text-right">
                                         <span class="px-1.5 py-0.5 rounded text-[10px] font-bold bg-green-100 text-green-700">{item.ctr}</span>
                                     </div>
                                     <div class="w-1/6 text-right text-gray-600">{item.conv}</div>
                                     <div class="w-1/6 text-right">
                                         <span class="text-[10px] font-bold text-brand-green">{item.status}</span>
                                     </div>
                                 </div>
                                 {/each}
                            </div>
                        </div>
                    </div>
                 </div>
             </div>
        </div>
        
        <!-- Bottom Grid of 3 items -->
        <div class="grid md:grid-cols-3 gap-0 mt-0 border-x border-b border-gray-200 divide-x divide-gray-200 bg-white">
            <div class="p-6 flex items-start gap-4 hover:bg-gray-50 transition-colors cursor-pointer">
                <div class="w-6 h-6 rounded-full border border-gray-300 flex-shrink-0 flex items-center justify-center text-xs font-mono">1</div>
                <p class="text-xs text-gray-600 leading-relaxed">Scan page content and analyze context in real-time to understand the perfect creative for each impression.</p>
            </div>
            <div class="p-6 flex items-start gap-4 hover:bg-gray-50 transition-colors cursor-pointer">
                <div class="w-6 h-6 rounded-full border border-gray-300 flex-shrink-0 flex items-center justify-center text-xs font-mono">2</div>
                <p class="text-xs text-gray-600 leading-relaxed">Generate unique ad creative with headlines, visuals, CTAs, and tone optimized for that specific moment and audience.</p>
            </div>
            <div class="p-6 flex items-start gap-4 hover:bg-gray-50 transition-colors cursor-pointer">
                <div class="w-6 h-6 rounded-full border border-gray-300 flex-shrink-0 flex items-center justify-center text-xs font-mono">3</div>
                <p class="text-xs text-gray-600 leading-relaxed">Learn from every impression to improve the next. Campaigns get smarter over time with accelerating ROI.</p>
            </div>
        </div>
    </div>
</section>