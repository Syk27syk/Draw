<template>
  <div class="h-full w-full bg-black text-white">
    <div id="navigation">
      <div id="title" class="flex flex-row py-3">
        <h1 class="my-auto text-lg font-bold px-5">Draw</h1>
        <p class="my-auto text-md px-5">2D and 3D drawing and generative art app for iPad and desktop</p>
      </div>
      <div id="menu" class="my-auto text-md px-5 py-2 bg-gray-500">
        <p> menu </p>
      </div>
      <div id="menu2" class="my-auto text-md px-5 py-2 bg-gray-500">
        <p> more menus </p>
      </div>
    </div>
    <div id="center" class="grid grid-cols-5 bg-white text-black h-full w-full">
      <div id="sidebar" class="col-span-1 h-screen px-5 py-5 border border-r-gray-500 border-t-0 border-b-0 border-l-0">
        <p class="text-center font-bold">SIDEBAR</p>
      </div>
      <div id="canvas" class="col-span-3 m-auto">
        <div class="text-black border border-gray-500 rounded-lg">
          <p class="m-auto px-48 py-48">canvas area</p>
        </div>
      </div>
      <div id="tools" class="col-span-1 h-screen px-5 py-5 border border-l-gray-500 border-t-0 border-b-0 border-r-0">
        <p class="text-center font-bold">TOOLS</p>
      </div>
    </div>
    <div id="bottom" class="py-36 m-auto bg-white text-black border border-t-gray-500 border-l-0 border-r-0 border-b-0">
      <p class="m-auto text-center px-5"> bottom section </p>
    </div>
    <div id="footer" class="text-sm text-center py-5 px-5">
      <p>All rights reserved 2022</p>
    </div>
  </div>
</template>
