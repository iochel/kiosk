<template>

<section class="block items-start w-full h-auto">

  <header class="w-full mb-40">
    <NavHeader />
  </header>
  
  <section class="z-0 mb-20 w-full h-auto">
    <slot />
  </section>
  
</section>

<footer class="fixed bottom-0 w-full z-20">
  <NavFooter />
</footer>

</template>
