<template>
<header data-layername="blogHeader" class="flex flex-col">
    <div data-layername="background" class="p-20 w-full bg-gray-100 max-md:px-5 max-md:max-w-full">
      <div class="flex gap-5 max-md:flex-col">
        <section data-layername="column" class="flex flex-col w-[55%] max-md:ml-0 max-md:w-full">
          <div class="flex flex-col items-start self-stretch my-auto w-full font-medium max-md:mt-10 max-md:max-w-full">
            <h2 data-layername="featuredPost" class="text-base leading-none text-gray-800 uppercase tracking-[3px]">
              Featured Post
            </h2>
            <h1 data-layername="stepByStepGuideToChoosingGreatFontPairs" class="self-stretch mt-5 text-4xl font-bold tracking-tighter leading-10 text-gray-800 max-md:max-w-full">
              Step-by-step guide to choosing great font pairs
            </h1>
            <p data-layername="byJohnDoeLMay232022" class="mt-4 text-sm leading-none text-amber-300">
              By <span class="text-amber-300">John Doe</span> l May 23, 2022
            </p>
            <p data-layername="duisAuteIrureDolorInReprehenderitInVoluptateVelitEsseCillumDoloreEuFugiatNullaPariaturExcepteurSintOccaecatCupidatatNonProident" class="self-stretch mt-4 text-base leading-7 text-zinc-500 max-md:max-w-full">
              Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.
            </p>
            <button data-layername="button" class="gap-3 px-12 py-4 mt-8 text-lg font-bold leading-none text-white bg-blue-600 max-md:px-5">
              Read More &gt;
            </button>
          </div>
        </section>
        <section data-layername="column" class="flex flex-col ml-5 w-[45%] max-md:ml-0 max-md:w-full">
          <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/c6b092768f7a218d448245a26948cf0fbc11baf915e08e348841ee64aa0cd10f?placeholderIfAbsent=true&apiKey=b642bcfadf164c35aebff8fb97b04ffb" alt="Featured post illustration" class="object-contain grow w-full aspect-[1.43] max-md:mt-10 max-md:max-w-full" />
        </section>
      </div>
    </div>
  </header>
  
  <main class="flex flex-col px-20 mt-16 w-full max-md:px-5 max-md:mt-10 max-md:max-w-full">
    <header>
      <h1 class="self-start text-5xl font-bold tracking-tighter leading-none text-gray-800 max-md:text-4xl">
        All posts
      </h1>
      <hr class="shrink-0 mt-8 h-px border border-solid bg-zinc-500 border-zinc-500 opacity-[0.32] max-md:max-w-full" />
    </header>

    <!-- Kontainer Artikel -->
    <article class="flex flex-col gap-4 mt-6">
      <!-- Artikel Pertama -->
      <section class="flex items-start gap-4 w-full max-md:flex-col">
        <img
          loading="lazy"
          src="https://cdn.builder.io/api/v1/image/assets/40e02fd5b45d48cd9235b37b246a760e/3a0be6a1f9097cb952a5de7feb721005b8d46fa8df024af017b76dc4b028d480?apiKey=40e02fd5b45d48cd9235b37b246a760e&"
          alt="Design tips article featured image"
          class="object-cover w-1/4 aspect-square max-md:w-full"
        />
        <div class="flex flex-col max-w-[75%] max-md:w-full">
          <p class="text-xs font-semibold text-orange-500 uppercase">Startup</p>
          <h2 class="text-lg font-semibold leading-tight text-gray-800">
            Design tips for designers that cover everything you need
          </h2>
          <p class="mt-1 text-gray-600 text-sm">
            Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.
          </p>
        </div>
      </section>

      <!-- Artikel Kedua -->
      <section class="flex items-start gap-4 w-full max-md:flex-col">
        <img
          loading="lazy"
          src="https://cdn.builder.io/api/v1/image/assets/40e02fd5b45d48cd9235b37b246a760e/166941846cc8a759998da1832ed117e392c3a909fb28a336b9a5dcca1aa8c9a3?apiKey=40e02fd5b45d48cd9235b37b246a760e&"
          alt="Web design clients article featured image"
          class="object-cover w-1/4 aspect-square max-md:w-full"
        />
        <div class="flex flex-col max-w-[75%] max-md:w-full">
          <p class="text-xs font-semibold text-orange-500 uppercase">Business</p>
          <h2 class="text-lg font-semibold leading-tight text-gray-800">
            How to build rapport with your web design clients
          </h2>
          <p class="mt-1 text-gray-600 text-sm">
            Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.
          </p>
        </div>
      </section>

      <!-- Artikel Ketiga -->
      <section class="flex items-start gap-4 w-full max-md:flex-col">
        <img
          loading="lazy"
          src="https://cdn.builder.io/api/v1/image/assets/40e02fd5b45d48cd9235b37b246a760e/4cfeccf80166a1a1e1a67e39fb048144c2077f71940df4513cedf2d316b6abdb?apiKey=40e02fd5b45d48cd9235b37b246a760e&"
          alt="Logo design trends article featured image"
          class="object-cover w-1/4 aspect-square max-md:w-full"
        />
        <div class="flex flex-col max-w-[75%] max-md:w-full">
          <p class="text-xs font-semibold text-orange-500 uppercase">Startup</p>
          <h2 class="text-lg font-semibold leading-tight text-gray-800">
            Logo design trends to avoid in 2022
          </h2>
          <p class="mt-1 text-gray-600 text-sm">
            Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.
          </p>
        </div>
      </section>

      <!-- Artikel Keempat -->
      <section class="flex items-start gap-4 w-full max-md:flex-col">
        <img
          loading="lazy"
          src="https://cdn.builder.io/api/v1/image/assets/40e02fd5b45d48cd9235b37b246a760e/fe6bc17e39e42108cfc446ef3fd97e7f17a962c19271f726d02e325ad5f94701?apiKey=40e02fd5b45d48cd9235b37b246a760e&"
          alt="Figma design systems article featured image"
          class="object-cover w-1/4 aspect-square max-md:w-full"
        />
        <div class="flex flex-col max-w-[75%] max-md:w-full">
          <p class="text-xs font-semibold text-orange-500 uppercase">Technology</p>
          <h2 class="text-lg font-semibold leading-tight text-gray-800">
            8 Figma design systems you can download for free today
          </h2>
          <p class="mt-1 text-gray-600 text-sm">
            Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.
          </p>
        </div>
      </section>

      <!-- Artikel Kelima -->
      <section class="flex items-start gap-4 w-full max-md:flex-col">
        <img
          loading="lazy"
          src="https://cdn.builder.io/api/v1/image/assets/40e02fd5b45d48cd9235b37b246a760e/3a0be6a1f9097cb952a5de7feb721005b8d46fa8df024af017b76dc4b028d480?apiKey=40e02fd5b45d48cd9235b37b246a760e&"
          alt="Font sizes article featured image"
          class="object-cover w-1/4 aspect-square max-md:w-full"
        />
        <div class="flex flex-col max-w-[75%] max-md:w-full">
          <p class="text-xs font-semibold text-orange-500 uppercase">Economy</p>
          <h2 class="text-lg font-semibold leading-tight text-gray-800">
            Font sizes in UI design: The complete guide to follow
          </h2>
          <p class="mt-1 text-gray-600 text-sm">
            Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.
          </p>
        </div>
      </section>
    </article>

    <nav class="flex gap-4 self-center mt-10 ml-3.5 max-w-full font-bold text-center w-[174px] max-md:mt-8">
      <button class="grow my-auto text-2xl leading-none text-zinc-500" aria-label="Previous page">
        &lt; Prev
      </button>
      <router-link to="/blog-posts" class="text-3xl tracking-tighter leading-none text-gray-800" aria-label="Next page">
        Next &gt;
      </router-link>
    </nav>
  </main>
</template>
