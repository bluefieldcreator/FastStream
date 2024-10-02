<script>
</script>

<svelte:head>
  <title>FastStream</title>
</svelte:head>

<div class="p-2 text-center text-white bg-black">
  <p class="text-3xl p-1 font-bold">Shiggy's Torrent App</p>
  <div class="space-x-3">
    <div class="p-1 bg-white rounded text-black w-max inline-block cursor-pointer">All Torrents</div>
    <div class="p-1 bg-white rounded text-black w-max inline-block cursor-pointer">Trackers</div>
  </div>  <script src="https://cdn.tailwindcss.com"></script>
</div>

<div class="p-2 border-2 my-2 rounded-lg w-3/4 mx-auto transition-all duration-500 hover:shadow bg-indigo-600">
  <div class="text-xl m-2 font-sans font-bold text-white">Arma.III.v2.06.elamigos-games.com.torrent</div>
  <div class="w-full bg-gray-200 rounded-lg h-4 mb-7">
    <div class="bg-blue-600 hover:bg-green-600 transition-all duration-500 shadow rounded-lg h-4" style="width: 20%"></div>
    <div class="text-center text-white text-lg font-bold">50% Downloaded</div>
  </div>
  <div class="border rounded-lg shadow text-white hover:bg-indigo-700 transition-all duration-300">
    <div class="m-2 font-bold">
      Peers:
      <div class="font-normal inline-block">11</div>
    </div>
    <div class="m-2 font-bold">
      Seeders:
      <div class="font-normal inline-block">3</div>
    </div>
    <div class="m-2 font-bold">
      Speed:
      <div class="inline-block text-indigo-200">▼ 30 Mbs</div>
      /
      <div class="inline-block text-blue-300 font-bold">▲ 30 Mbs</div>
    </div>
  </div>

  <div class="inline-block border-2 font-bold text-white p-1 m-1 border-blue-500 rounded hover:bg-blue-500 hover:text-white transition-all duration-500 cursor-pointer">Open File Location</div>
  <div class="inline-block m-1 text-white font-bold border-green-500 border-2 p-1 rounded hover:bg-green-500 hover:text-white transition-all duration-500 cursor-pointer">Copy Magnet Link</div>
</div>

<style lang="scss">

</style>
