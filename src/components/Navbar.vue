<template lang="">
   <!-- Navbar -->
   <div class="navbar bg-slate-500">
      <!-- Nav Logo -->
      <div class="flex-1">
         <a class="btn btn-ghost normal-case text-xl">daisyUI</a>
      </div>
      <!-- End Nav Logo -->

      <!-- Nav Menu if Dekstop View -->
      <div class="navbar-center hidden lg:flex">
         <ul class="menu menu-horizontal px-1">
            <li><a>Produk</a></li>
            <li><a>Galeri</a></li>
            <li><a>Blog</a></li>
            <li><a>Tentang Kami</a></li>
            <li><a>Hubungi Kami</a></li>
            <li><a>Masuk</a></li>
         </ul>
      </div>
      <!-- End Nav Menu if Dekstop View -->

      <!-- Nav Menu Tablet View -->
      <div class="navbar-center hidden md:flex lg:hidden">
         <ul class="menu menu-horizontal px-1">
            <li><a>Produk</a></li>
            <li><a>Blog</a></li>
            <li><a>Masuk</a></li>
         </ul>
      </div>
      <!-- End Nav Menu Tablet View -->

      <!-- Nav Toggle if Mobile View -->
      <div class="flex-none">
         <div class="dropdown dropdown-end">
            <label tabindex="0" class="btn btn-ghost md:hidden lg:hidden">
               <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h8m-8 6h16" />
               </svg>
            </label>
            <ul tabindex="0" class="menu menu-compact dropdown-content mt-3 p-2 shadow bg-base-100 rounded-box w-52">
               <li>
                  <a class="justify-between">
                     Produk
                     <span class="badge">New</span>
                  </a>
               </li>
               <li><a>Galeri</a></li>
               <li><a>Blog</a></li>
               <li><a>Tentang Kami</a></li>
               <li><a>Hubungi Kami</a></li>
               <li><a>Masuk</a></li>
            </ul>
         </div>
      </div>
      <!-- End Nav Toggle if Mobile View -->
   </div>
   <!-- End Mavbar -->
</template>
<script>
export default {};
</script>
<style lang="en"></style>
