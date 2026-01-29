<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <title>Ecommerce Page</title>

  </head>
<body>

    <!-- header started -->
    <header class="text-gray-600 body-font">
  <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
    <a class="flex title-font font-medium items-center text-gray-900 mb-4 md:mb-0">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 bg-yellow-500 rounded-full" viewBox="0 0 24 24">
        <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
      </svg>
      <span class="ml-3 text-xl">Daraz</span>
    </a>
    <nav class="md:mr-auto md:ml-4 md:py-1 md:pl-4 md:border-l md:border-gray-400	flex flex-wrap items-center text-base justify-center">
      <a class="mr-5 hover:text-gray-900">Home</a>
      <a class="mr-5 hover:text-gray-900">About</a>
      <a class="mr-5 hover:text-gray-900">Purchase</a>
      <a class="mr-5 hover:text-gray-900">Email</a>
    </nav>
    <button class="inline-flex items-center bg-gray-100 border-0 py-1 px-3 focus:outline-none hover:bg-gray-200 rounded text-base mt-4 md:mt-0">Button
      <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-1" viewBox="0 0 24 24">
        <path d="M5 12h14M12 5l7 7-7 7"></path>
      </svg>
    </button>
  </div>
</header>
<!-- header ended -->

<!-- slider started -->
 
<div class="container mx-auto px-5">
<div id="default-carousel" class="relative w-full" data-carousel="slide">
    <!-- Carousel wrapper -->
    <div class="relative h-56 overflow-hidden rounded-base md:h-96">
         <!-- Item 1 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img src="https://img.lazcdn.com/us/domino/5a8ab1af-6d17-413c-9aec-c702be4322bd_PK-1976-688.jpg_2200x2200q80.jpg_.avif" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
        </div>
        <!-- Item 2 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img src="https://img.lazcdn.com/us/domino/4fc1c97a-d588-476b-b5fa-eead5f82ea2b_PK-1976-688.jpg_2200x2200q80.jpg_.avif" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
        </div>
        <!-- Item 3 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img src="https://img.lazcdn.com/us/domino/7ef00093-4ac5-4c63-ab1a-62cc141a4247_PK-1976-688.jpg_2200x2200q80.jpg_.avif" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
        </div>
        <!-- Item 4 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img src="https://img.lazcdn.com/us/domino/261024d2-bee0-48be-87cb-2e02588c725c_PK-1976-688.jpg_2200x2200q80.jpg_.avif" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
        </div>
        <!-- Item 5 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img src="https://img.lazcdn.com/us/domino/14dbc209-757f-43f6-91e8-1070b394fc09_PK-1976-688.jpg_2200x2200q80.jpg_.avif" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
        </div>
    </div>

    <!-- Slider indicators -->
    <div class="absolute z-30 flex -translate-x-1/2 bottom-5 left-1/2 space-x-3 rtl:space-x-reverse">
        <button type="button" class="w-3 h-3 rounded-base" aria-current="true" aria-label="Slide 1" data-carousel-slide-to="0"></button>
        <button type="button" class="w-3 h-3 rounded-base" aria-current="false" aria-label="Slide 2" data-carousel-slide-to="1"></button>
        <button type="button" class="w-3 h-3 rounded-base" aria-current="false" aria-label="Slide 3" data-carousel-slide-to="2"></button>
        <button type="button" class="w-3 h-3 rounded-base" aria-current="false" aria-label="Slide 4" data-carousel-slide-to="3"></button>
        <button type="button" class="w-3 h-3 rounded-base" aria-current="false" aria-label="Slide 5" data-carousel-slide-to="4"></button>
    </div>
    <!-- Slider controls -->
    <button type="button" class="absolute top-0 start-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none" data-carousel-prev>
        <span class="inline-flex items-center justify-center w-10 h-10 rounded-base bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
            <svg class="w-5 h-5 text-white rtl:rotate-180" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24"><path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m15 19-7-7 7-7"/></svg>
            <span class="sr-only">Previous</span>
        </span>
    </button>
    <button type="button" class="absolute top-0 end-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none" data-carousel-next>
        <span class="inline-flex items-center justify-center w-10 h-10 rounded-base bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
            <svg class="w-5 h-5 text-white rtl:rotate-180" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24"><path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m9 5 7 7-7 7"/></svg>
            <span class="sr-only">Next</span>
        </span>
    </button>
</div>
</div>
<!-- slider ended -->
 
 <!-- ecommerce started -->
  <section class="text-gray-600 body-font">
  <div class="container px-5 py-24 mx-auto">
    <div class="flex flex-wrap -m-4">
      <div class="lg:w-1/4 md:w-1/2 p-4 w-full">
        <a href="nestle.html" class="block relative h-48 rounded overflow-hidden">
          <img alt="ecommerce" class="object-cover object-center w-full h-full block" src="https://img.drz.lazcdn.com/static/pk/p/6aaf7dfec24dd38e276b6afac08d5326.jpg_400x400q80.jpg_.avif420x260">
        </a>
        <div class="mt-4">
          <h3 class="text-gray-500 text-xs tracking-widest title-font mb-1">CATEGORY</h3>
          <h2 class="text-gray-900 title-font text-lg font-medium">Nestle- Cerelac 3 Fruits & Wheat Baby Food 350</h2>
          <p class="mt-1">Rs. 737</p>
        </div>
      </div>
      <div class="lg:w-1/4 md:w-1/2 p-4 w-full">
        <a href="glasses.html" class="block relative h-48 rounded overflow-hidden">
          <img alt="ecommerce" class="object-cover object-center w-full h-full block" src="https://img.drz.lazcdn.com/g/kf/S965c0a9a0f124bef8fb484353cfdb7ceK.jpg_200x200q80.jpg_.avif">
        </a>
        <div class="mt-4">
          <h3 class="text-gray-500 text-xs tracking-widest title-font mb-1">CATEGORY</h3>
          <h2 class="text-gray-900 title-font text-lg font-medium">Blue Light Filtered Protective Glasses UV400 filtered mineral glass Computer Glasses for Men and Women Eye Protective Glasses Screen Glasses</h2>
          <p class="mt-1">Rs. 567</p>
        </div>
      </div>
      <div class="lg:w-1/4 md:w-1/2 p-4 w-full">
        <a href="laptopbag.html" class="block relative h-48 rounded overflow-hidden">
          <img alt="ecommerce" class="object-cover object-center w-full h-full block" src="https://img.drz.lazcdn.com/static/pk/p/24b82c3876c311bdf687dcf68dee70ba.jpg_200x200q80.jpg_.avif">
        </a>
        <div class="mt-4">
          <h3 class="text-gray-500 text-xs tracking-widest title-font mb-1">CATEGORY</h3>
          <h2 class="text-gray-900 title-font text-lg font-medium">Dell Pro Sleeve 13 (Original)</h2>
          <p class="mt-1">Rs.1200</p>
        </div>
      </div>
      <div class="lg:w-1/4 md:w-1/2 p-4 w-full">
        <a href="airbuds.html" class="block relative h-48 rounded overflow-hidden">
          <img alt="ecommerce" class="object-cover object-center w-full h-full block" src="https://img.drz.lazcdn.com/static/pk/p/01fbb0806fd32488e9a2c3144d96c7cc.jpg_200x200q80.jpg_.avif">
        </a>
        <div class="mt-4">
          <h3 class="text-gray-500 text-xs tracking-widest title-font mb-1">CATEGORY</h3>
          <h2 class="text-gray-900 title-font text-lg font-medium">Airpods_Pro Wireless Earbuds Bluetooth 5.0 Compatible with IOS and Android Both</h2>
          <p class="mt-1">Rs.2000</p>
        </div>
      </div>
      <div class="lg:w-1/4 md:w-1/2 p-4 w-full">
        <a class="block relative h-48 rounded overflow-hidden">
          <img alt="ecommerce" class="object-cover object-center w-full h-full block" src="https://img.drz.lazcdn.com/g/kf/Sddfb51d3f1b1468c9e943e1c01229fe4F.jpg_200x200q80.jpg_.avif">
        </a>
        <div class="mt-4">
          <h3 class="text-gray-500 text-xs tracking-widest title-font mb-1">CATEGORY</h3>
          <h2 class="text-gray-900 title-font text-lg font-medium">Quality Laptop bag , Backpack, Travel bag</h2>
          <p class="mt-1">Rs.700</p>
        </div>
      </div>
      <div class="lg:w-1/4 md:w-1/2 p-4 w-full">
        <a class="block relative h-48 rounded overflow-hidden">
          <img alt="ecommerce" class="object-cover object-center w-full h-full block" src="https://img.drz.lazcdn.com/static/pk/p/e939183caa2f07b9faf2d81a52a2ea92.jpg_200x200q80.jpg_.avif">
        </a>
        <div class="mt-4">
          <h3 class="text-gray-500 text-xs tracking-widest title-font mb-1">CATEGORY</h3>
          <h2 class="text-gray-900 title-font text-lg font-medium">2600mah-Portable Power Bank, Usb Port,Input and Output Fast Charge</h2>
          <p class="mt-1">Rs.5000</p>
        </div>
      </div>
      <div class="lg:w-1/4 md:w-1/2 p-4 w-full">
        <a class="block relative h-48 rounded overflow-hidden">
          <img alt="ecommerce" class="object-cover object-center w-full h-full block" src="https://img.drz.lazcdn.com/static/pk/p/aa4244fdc1e20e2f6e938393b7eff7e8.jpg_200x200q80.jpg_.avif">
        </a>
        <div class="mt-4">
          <h3 class="text-gray-500 text-xs tracking-widest title-font mb-1">CATEGORY</h3>
          <h2 class="text-gray-900 title-font text-lg font-medium">Softy sandal for boy's || sandal for men || New Stylish and Trending sandal for boys</h2>
          <p class="mt-1">Rs.300</p>
        </div>
      </div>
      <div class="lg:w-1/4 md:w-1/2 p-4 w-full">
        <a class="block relative h-48 rounded overflow-hidden">
          <img alt="ecommerce" class="object-cover object-center w-full h-full block" src="https://img.drz.lazcdn.com/g/kf/Sebffdc39d3e245d0ab7bb8fd2c9e36df0.jpg_200x200q80.jpg_.avif">
        </a>
        <div class="mt-4">
          <h3 class="text-gray-500 text-xs tracking-widest title-font mb-1">CATEGORY</h3>
          <h2 class="text-gray-900 title-font text-lg font-medium">CHILL FITNESS Rubber Coated Dumbbells with Metal Handles| Dumbbell| Anti Slip Metal Handles| Fitness Home Gym Exercise Dumbbels 1kg, 2kg, 3kg, 4kg, 5kg, 6kg, 7kg, 8kg,10kg Single piece Buy pair add to cart 2</h2>
          <p class="mt-1">Rs.850</p>
        </div>
      </div>
    </div>
  </div>
</section>
 <!-- ecommerce ended -->




<script src="https://cdn.jsdelivr.net/npm/flowbite@4.0.1/dist/flowbite.min.js"></script>

</body>
</html>
{--}
