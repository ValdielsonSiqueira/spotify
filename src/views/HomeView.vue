<template>
  <div class="h-screen flex flex-col">
    <div class="flex flex-1">
      <aside class="w-72 bg-zinc-950 p-6">
        <div class="flex items-center gap-2">
          <div  class="h-3 w-3 bg-red-500 rounded-full"/>
          <div  class="h-3 w-3 bg-yellow-500 rounded-full"/>
          <div  class="h-3 w-3 bg-green-500 rounded-full"/>
        </div>
        <nav class="space-y-5 mt-10">
          <a href="" class="flex items-center gap-2 text-sm font-semibold text-zinc-200">
            <mdicon name="Home" /> 
            Início 
          </a>
          <a href="" class="flex items-center gap-2 text-sm font-semibold text-zinc-200">
            <mdicon name="SearchWeb" /> 
            Buscar 
          </a>
          <a href="" class="flex items-center gap-2 text-sm font-semibold text-zinc-200" >
            <mdicon name="Bookshelf" /> 
            Sua Biblioteca 
          </a>
        </nav>
        <nav class="mt-6 pt-6 border-t border-zinc-800 flex flex-col gap-3"> 
          <a href="" class="text-sm text-zinc-400 ">Hot Hits Brasil</a>
          <a href="" class="text-sm text-zinc-400 ">Indiespensável</a>
          <a href="" class="text-sm text-zinc-400 ">Metal Cover</a>
          <a href="" class="text-sm text-zinc-400 ">Top Brasil</a>
        </nav>
      </aside>
      <main class="flex-1 p-6 bg-zinc-900">
        <div class="flex items-center gap-4">
          <button class="rounded-full bg-black/40 p-1">
            <mdicon name="ChevronLeft" /> 
          </button>
          <button class="rounded-full bg-black/40 p-1">
            <mdicon name="ChevronRight" /> 
          </button>
        </div> 
        <h1 class="font-semibold text-3xl mt-10">Boa tarde</h1>
        <div class="grid grid-cols-3 gap-4 mt-4">
          <a href="#" class="bg-white/5 group flex items-center gap-4 rounded overflow-hidden hover:bg-white/10 transition-colors">
            <img src="../assets/album.jpg" width="104" height="104" alt="Album">
            <strong>The Final Frontier</strong>
            <button class="w-12 h-12 flex items-center justify-center pl-0.5 rounded-full bg-green-400 text-black ml-auto mr-8 invisible group-hover:visible">
              <mdicon name="play" />
            </button>
          </a>
          <a href="#" class="bg-white/5 group flex items-center gap-4 rounded overflow-hidden hover:bg-white/10 transition-colors">
              <img src="../assets/album.jpg" width="104" height="104" alt="Album">
              <strong>The Final Frontier</strong>
              <button class="w-12 h-12 flex items-center justify-center pl-0.5 rounded-full bg-green-400 text-black ml-auto mr-8 invisible group-hover:visible">
                <mdicon name="play" />
              </button>
          </a>
          <a href="#" class="bg-white/5 group flex items-center gap-4 rounded overflow-hidden hover:bg-white/10 transition-colors">
              <img src="../assets/album.jpg" width="104" height="104" alt="Album">
              <strong>The Final Frontier</strong>
              <button class="w-12 h-12 flex items-center justify-center pl-0.5 rounded-full bg-green-400 text-black ml-auto mr-8 invisible group-hover:visible">
                <mdicon name="play" />
              </button>
          </a>
          <a href="#" class="bg-white/5 group flex items-center gap-4 rounded overflow-hidden hover:bg-white/10 transition-colors">
              <img src="../assets/album.jpg" width="104" height="104" alt="Album">
              <strong>The Final Frontier</strong>
              <button class="w-12 h-12 flex items-center justify-center pl-0.5 rounded-full bg-green-400 text-black ml-auto mr-8 invisible group-hover:visible">
                <mdicon name="play" />
              </button>
          </a>
          <a href="#" class="bg-white/5 group flex items-center gap-4 rounded overflow-hidden hover:bg-white/10 transition-colors">
              <img src="../assets/album.jpg" width="104" height="104" alt="Album">
              <strong>The Final Frontier</strong>
              <button class="w-12 h-12 flex items-center justify-center pl-0.5 rounded-full bg-green-400 text-black ml-auto mr-8 invisible group-hover:visible">
                <mdicon name="play" />
              </button>
          </a>
          <a href="#" class="bg-white/5 group flex items-center gap-4 rounded overflow-hidden hover:bg-white/10 transition-colors">
              <img src="../assets/album.jpg" width="104" height="104" alt="Album">
              <strong>The Final Frontier</strong>
              <button class="w-12 h-12 flex items-center justify-center pl-0.5 rounded-full bg-green-400 text-black ml-auto mr-8 invisible group-hover:visible">
                <mdicon name="play" />
              </button>
          </a>
        </div>
        <h2 class="font-semibold text-2xl mt-10">Feito para valdielson.siqueira</h2>
        <div class="grid grid-cols-5 gap-4 mt-4">
          <a href="" class="bg-white/5 p-3 flex flex-col gap-2 rounded-md hover:bg-white/10">
            <img class="w-full" src="../assets/album.jpg" width="120" height="120" alt="Album">
            <strong class="font-semibold">Daily Mix 1</strong>
            <span class="text-sm text-zinc-500">Megadeth, Metallica, Kreator e mais</span>
          </a>
          <a href="" class="bg-white/5 p-3 flex flex-col gap-2 rounded-md hover:bg-white/10">
              <img class="w-full" src="../assets/album.jpg" width="120" height="120" alt="Album">
              <strong class="font-semibold">Daily Mix 1</strong>
              <span class="text-sm text-zinc-500">Megadeth, Metallica, Kreator e mais</span>
          </a>
          <a href="" class="bg-white/5 p-3 flex flex-col gap-2 rounded-md hover:bg-white/10">
              <img class="w-full" src="../assets/album.jpg" width="120" height="120" alt="Album">
              <strong class="font-semibold">Daily Mix 1</strong>
              <span class="text-sm text-zinc-500">Megadeth, Metallica, Kreator e mais</span>
          </a>
          <a href="" class="bg-white/5 p-3 flex flex-col gap-2 rounded-md hover:bg-white/10">
              <img class="w-full" src="../assets/album.jpg" width="120" height="120" alt="Album">
              <strong class="font-semibold">Daily Mix 1</strong>
              <span class="text-sm text-zinc-500">Megadeth, Metallica, Kreator e mais</span>
          </a>
          <a href="" class="bg-white/5 p-3 flex flex-col gap-2 rounded-md hover:bg-white/10">
              <img class="w-full" src="../assets/album.jpg" width="120" height="120" alt="Album">
              <strong class="font-semibold">Daily Mix 1</strong>
              <span class="text-sm text-zinc-500">Megadeth, Metallica, Kreator e mais</span>
          </a>
        </div>
      </main>
    </div>
    <footer class="bg-zinc-800 border-t border-zinc-700 px-6 py-4 flex items-center justify-between">
      <div class="flex items-center gap-3">
        <img src="../assets/album.jpg" width="56" height="56" alt="Album">
        <div class="flex flex-col">
          <strong class="font-normal">The Final Frontier</strong>
          <span class="text-xs text-zinc-500">Iron Maiden</span>
        </div>
      </div>
      <div class="flex flex-col items-center gap-2">
        <div class="flex items-center gap-6">
          <mdicon size="20" name="ShuffleVariant" class="text-zinc-200"/>          
          <mdicon size="20" name="SkipPrevious" class="text-zinc-200"/>
          <button class="w-10 h-10 flex items-center justify-center pl-0.5 rounded-full bg-white text-black ml-auto">
            <mdicon name="play" />
          </button>          
          <mdicon size="20" name="SkipNext" class="text-zinc-200"/>
          <mdicon size="20" name="Repeat" class="text-zinc-200"/>
        </div>
        <div class="flex items-center gap-2">
          <span class="text-xs text-zinc-400">0:22</span>
          <div class="h-1 rounded-full w-96 bg-zinc-600">
            <div class="bg-zinc-200 w-40 h-1 rounded-full" />
          </div>
          <span class="text-xs text-zinc-400">2:20</span>
        </div>
      </div>
      <div class="flex items-center gap-4">
        <mdicon size="20" name="Microphone" class="text-zinc-200"/>
        <mdicon size="20" name="FormatListBulleted" class="text-zinc-200"/>
        <mdicon size="20" name="Devices" class="text-zinc-200"/>
        <div class="flex items-center gap-2">
          <mdicon size="20" name="VolumeHigh" class="text-zinc-200"/>
          <div class="h-1 rounded-full w-24 bg-zinc-600">
            <div class="bg-zinc-200 w-10 h-1 rounded-full" />
          </div>
        </div>
        <mdicon size="20" name="Overscan" class="text-zinc-200"/>
      </div>
    </footer>
  </div>
</template>

<script>
  export default {
    name: "HomeView",
    components: {    
    },
  }
</script>
