<nav class="lg:px-16 px-6 bg-gray-100 text-black shadow-md flex flex-wrap items-center lg:py-0 py-2">
    <div class="flex-1 flex justify-between items-center">
      <!-- LOGO -->
        <a href="/" class="flex text-lg font-semibold">
        	<img src="/logo.svg" width="50" height="50" class="p-2" alt="Wilovy LOGO">
      	</a>
    </div>
    <label for="menu-toggle" class="cursor-pointer lg:hidden block">
      <svg class="fill-current text-black" xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20">
        <title>Menu</title>
        <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
      </svg>
    </label>
    <input class="hidden" type="checkbox" id="menu-toggle">
    <div class="hidden lg:flex lg:items-center lg:w-auto w-full" id="menu">
      <nav>
        <ul class="text-xl text-center items-center gap-x-5 pt-4 md:gap-x-4 lg:text-lg lg:flex  lg:pt-0">
          <li class="py-2 lg:py-0">
            <a class="inline-flex flex-col items-center justify-center px-5 hover:bg-gray-100 group" href="/">
            <span class="text-sm text-black group-hover:text-green-500">Home</span>
            </a>
          </li>
        </ul>
      </nav>
    </div>
  </nav>

<style>
    #menu-toggle:checked + #menu {
        display: block;
    }
</style>