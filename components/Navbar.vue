<template>
    <div>
        <header class="lg:px-16 px-6 bg-white flex flex-wrap items-center lg:py-0 py-2">
            <div class="flex-1 flex justify-between items-center">
                <a href="" class="text-red-700"><h5>ROADMANN</h5></a>
              </div>
                <label for="menu-toggle" class="cursor-pointer lg:hidden block">
                  <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
                </label>
                <input type="checkbox" class="hidden" id="menu-toggle" />
                <div class="hidden lg:flex lg:items-center lg:w-auto w-full" id="menu">
                    <nav>
                        <ul class="lg:flex items-center justify-between text-base text-gray-700 pt-4 lg:pt-0"> 
                          <li>
                            <a href="#" class="lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-red-700">About</a>
                          </li>
                          <li>
                            <a href="#" class="lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-red-700">Artist</a>
                          </li>
                          <li>
                            <a href="#" class="lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-red-700">Event</a>
                          </li>
                          <li>
                            <a href="#" class="lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-red-700">Media</a>
                          </li>
                          <li>
                            <a href="#" class="lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-red-700">Partner</a>
                          </li>
                          <li>
                            <a href="#" class="lg:p-4 py-3 px-0 block border-b-2 border-transparent hover:border-red-700">Shop</a>
                          </li>
                        </ul>
                    </nav>
                </div>
                </header>
            </div>
</template>
<script>
export default {
     link: [
        {
          rel: 'stylesheet',
          href: 'https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap'
        }
      ]  
}
</script>
<style scoped>
  #menu-toggle:checked + #menu {
    display: block;
  }
  h5{
      font-family: "Playfair Display";
      font-size: 36px; 
      font-style: normal; 
      font-weight: bold; 
      line-height: 48px;
  }
  a{
    font-family: 'Poppins', sans-serif;
    font-style: normal;
    font-weight: 600;
    font-size: 18px;
    line-height: 27px;
  }
</style>