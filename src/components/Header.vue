<template>
  <header class="absolute top-0 w-full py-7 flex items-center bg-transparent">
    <div class="flex items-center justify-between container">
      <h1 class="text-xl uppercase">Calinho Calhas</h1>
      <nav class="hidden sm:flex">
        <ul class="inline-flex gap-10 list-none uppercase">
            <li class="hover:scale-[1.01]">
                <a href="#services" class="text-sm hover:scale-[1.01] bg-transparent">
                    Serviços
                </a>
            </li>
            <li class="hover:scale-[1.01]">
                <a href="#contact" class="text-sm hover:scale-[1.01] bg-transparent">
                    Fale conosco
                </a>
            </li>
        </ul>
      </nav>
      <div class="inline-flex items-center justify-center gap-5">
        <div>
          <a
            href="tel:+5547999797075"
            class="flex items-center justify-center gap-2 text-sm bg-transparent cursor-pointer"
          >
            <img
              src="../assets/icons/telephone.png"
              alt="Telefone"
              class="size-[15px]"
            />
            <p class="hidden md:block hover:scale-[1.01] cursor-pointer">+55 47 99979 7075</p>
          </a>
        </div>
      </div>
    </div>
  </header>
</template>