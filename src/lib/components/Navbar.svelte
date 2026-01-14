<script>
  import { onMount } from 'svelte';
  
  let isScrolled = false;

  onMount(() => {
    const handleScroll = () => {
      isScrolled = window.scrollY > 0;
    };
    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  });
</script>

<div class="fixed top-0 w-full z-50 flex flex-col font-sans">
  <!-- Top Banner -->
  <div class="bg-[#F3F4F6] border-b border-gray-200 py-2 px-4 text-center text-[10px] sm:text-xs font-medium tracking-wide text-gray-900">
    <span class="mr-1">AI-First SEO: 2024 Playbook with Kevin Indig & Sam Smith on Dec 11</span>
    <a href="#" class="inline-flex items-center hover:underline font-bold ml-1">
      SAVE YOUR SPOT 
      <svg class="w-3 h-3 ml-0.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
    </a>
  </div>

  <!-- Main Nav -->
  <nav class="bg-white/95 backdrop-blur-sm border-b border-gray-100 transition-all duration-200 {isScrolled ? 'py-3' : 'py-4'}">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex items-center justify-between">
      <!-- Logo -->
      <div class="flex items-center">
        <a href="/" class="flex items-center gap-2">
          <svg width="32" height="32" viewBox="0 0 97 96" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path opacity="0.7" d="M65.0783 2.33158C71.8335 9.07503 63.4367 28.3905 46.3235 45.4739C29.2105 62.5574 9.86132 70.9395 3.10614 64.1962C-3.64905 57.4526 4.74774 38.1372 21.8609 21.0537C38.9739 3.9703 58.323 -4.41188 65.0783 2.33158Z" fill="#0A0D12"/>
            <path opacity="0.5" d="M79.7599 16.9832C86.5152 23.7267 78.1183 43.0422 61.0051 60.1256C43.8919 77.2091 24.543 85.5912 17.7878 78.8479C11.0326 72.1043 19.4294 52.7889 36.5424 35.7054C53.6556 18.6219 73.0047 10.2398 79.7599 16.9832Z" fill="#0A0D12"/>
            <path opacity="0.3" d="M94.4357 31.6366C101.191 38.3801 92.7941 57.6956 75.6811 74.7791C58.5679 91.8625 39.2189 100.245 32.4636 93.5013C25.7083 86.7577 34.1052 67.4423 51.2184 50.3588C68.3314 33.2753 87.6806 24.8933 94.4357 31.6366Z" fill="#0A0D12"/>
          </svg>
          <span class="text-2xl font-sans font-bold tracking-tight text-gray-900">LoudEcho</span>
        </a>
        
        <!-- Desktop Links -->
        <div class="hidden md:flex items-center ml-10 space-x-8 text-sm font-medium text-gray-600">
          <a href="#" class="hover:text-gray-900">Platform</a>
          <a href="#" class="hover:text-gray-900">Solutions</a>
          <a href="#" class="hover:text-gray-900">Resources</a>
          <a href="#" class="hover:text-gray-900">Pricing</a>
        </div>
      </div>

      <!-- Right Actions -->
      <div class="flex items-center space-x-4 sm:space-x-6">
        <a href="#" class="hidden md:block text-sm font-medium text-gray-600 hover:text-gray-900">Sign In</a>
        <a href="#" class="hidden md:block text-sm font-medium text-gray-600 hover:text-gray-900">Watch Demo</a>
        <a href="#" class="inline-flex items-center justify-center px-4 py-2 border border-transparent text-sm font-medium rounded-full text-white bg-gray-900 hover:bg-gray-800 transition-colors shadow-sm">
          Request Access
          <svg class="w-4 h-4 ml-1" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
        </a>
      </div>
    </div>
  </nav>
</div>
