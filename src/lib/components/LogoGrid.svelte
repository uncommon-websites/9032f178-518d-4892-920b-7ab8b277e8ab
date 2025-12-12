<script>
    const logos = [
        { name: 'Forbes' },
        { name: 'TechCrunch' },
        { name: 'The Verge' },
        { name: 'Wired' },
        { name: 'Bloomberg' },
        { name: 'CNN' },
        { name: 'Business Insider' },
        { name: 'The Guardian' },
        { name: 'NYTimes' },
        { name: 'WSJ' },
        { name: 'Reuters' },
        { name: 'Vox' },
        { name: 'Mashable' },
        { name: 'Engadget' },
        { name: 'Axios' }
    ];
</script>

<section class="py-12 bg-white border-b border-gray-200 font-sans">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <p class="text-center text-[10px] uppercase tracking-widest text-gray-500 font-bold mb-8">
            SERVING ADS ON LEADING PUBLISHERS
        </p>

        <div class="grid grid-cols-2 md:grid-cols-5 gap-0 border-t border-l border-gray-200">
            {#each logos as logo}
                <div class="flex items-center justify-center p-6 border-r border-b border-gray-200 h-24 relative group">
                    <!-- Logo Placeholder -->
                    <span class="text-base md:text-lg font-bold text-gray-300 group-hover:text-gray-600 transition-colors">
                        {logo.name}
                    </span>
                </div>
            {/each}
        </div>
    </div>
</section>
