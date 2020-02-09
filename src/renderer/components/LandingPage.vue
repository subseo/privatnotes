<template>
  <div class="flex flex-col h-screen text-sm text-gray-800">
    <div class="flex-1 flex overflow-y-hidden">
      <!-- REPOSITORY WRAPPER -->
      <div class="sidebar bg-gray-300 w-48 flex-none flex flex-col justify-between">
        <!-- REPOSITORY HEADER -->
        <div class="sidebar-header">
          <ul class="py-6 bg-gray-400">
            <li>Admin Menü</li>
          </ul>
        </div>
        <!-- REPOSITORY LIST -->
        <div class="sidebar-projectlist overflow-y-auto px-5 mt-2 h-full">
          <h3 class="tracking-widest text-gray-500 font-normal text-xs uppercase">Projekte</h3>
          <ul>
            <li>
              Repository A
            </li>
            <li>
              <ul class="leading-extra-loose pl-3">
                <li class="truncate"><a href="#" class="hover:text-white">Folder A</a>
                  <ul class="pl-3">
                    <li class="truncate"><a href="#" class="hover:text-white">Subfolder A</a></li>
                    <li class="truncate"><a href="#" class="hover:text-white">Subfolder B</a></li>
                  </ul>
                </li>
              </ul>
            </li>
            <li>
              <ul class="leading-extra-loose pl-3">
                <li class="truncate"><a href="#" class="hover:text-white">Folder B</a>
                  <ul class="pl-3">
                    <li class="truncate"><a href="#" class="hover:text-white">Subfolder A</a></li>
                    <li class="truncate"><a href="#" class="hover:text-white">Subfolder B</a></li>
                  </ul>
                </li>
              </ul>
            </li>
            <li>
              Repository B
            </li>
            <li>
              <ul class="leading-extra-loose pl-3">
                <li class="truncate"><a href="#" class="hover:text-white">Folder A</a>
                  <ul class="pl-3">
                    <li class="truncate"><a href="#" class="hover:text-white">Subfolder A</a></li>
                    <li class="truncate"><a href="#" class="hover:text-white">Subfolder B</a></li>
                  </ul>
                </li>
              </ul>
            </li>
            <li>
              <ul class="leading-extra-loose pl-3">
                <li class="truncate"><a href="#" class="hover:text-white">Folder B</a>
                  <ul class="pl-3">
                    <li class="truncate"><a href="#" class="hover:text-white">Subfolder A</a></li>
                    <li class="truncate"><a href="#" class="hover:text-white">Subfolder B</a></li>
                  </ul>
                </li>
              </ul>
            </li>

          </ul>
        </div>
        <!-- REPOSITORY FOOTER -->
        <div class="bg-gray-500 h-16 px-4 py-2 flex items-center group">
          <svg class="fill-current text-gray-600 w-8 h-8 group-hover:text-white" viewBox="0 0 24 24" width="24" height="24"><path class="heroicon-ui" d="M12 22a10 10 0 110-20 10 10 0 010 20zm0-2a8 8 0 100-16 8 8 0 000 16zm1-9h2a1 1 0 010 2h-2v2a1 1 0 01-2 0v-2H9a1 1 0 010-2h2V9a1 1 0 012 0v2z"/></svg>
          <a href="#" class="font-normal text-gray-500 ml-2 group-hover:text-white">New Playlist</a>
        </div>
      </div>

      <!-- FILES WRAPPER -->
      <div class="sidebar bg-gray-500 w-64 flex-none flex flex-col justify-between">
        <!-- FILES HEADER -->
        <div class="sidebar-header">
          <ul class="py-6 bg-gray-600">
            <li>Admin Menü</li>
          </ul>
        </div>
        <!-- FILES PROJECT LIST -->
        <div class="sidebar-projectlist overflow-y-auto px-5 mt-2 h-full">
          <h3 class="tracking-widest text-gray-500 font-normal text-xs uppercase">Projekte</h3>
          <ul>
            <li>
              Repository A
            </li>
            <li>
              <ul class="leading-extra-loose pl-3">
                <li class="truncate"><a href="#" class="hover:text-white">Folder A</a>
                  <ul class="pl-3">
                    <li class="truncate"><a href="#" class="hover:text-white">Subfolder A</a></li>
                    <li class="truncate"><a href="#" class="hover:text-white">Subfolder B</a></li>
                  </ul>
                </li>
              </ul>
            </li>
            <li>
              <ul class="leading-extra-loose pl-3">
                <li class="truncate"><a href="#" class="hover:text-white">Folder B</a>
                  <ul class="pl-3">
                    <li class="truncate"><a href="#" class="hover:text-white">Subfolder A</a></li>
                    <li class="truncate"><a href="#" class="hover:text-white">Subfolder B</a></li>
                  </ul>
                </li>
              </ul>
            </li>
            <li>
              Repository B
            </li>
            <li>
              <ul class="leading-extra-loose pl-3">
                <li class="truncate"><a href="#" class="hover:text-white">Folder A</a>
                  <ul class="pl-3">
                    <li class="truncate"><a href="#" class="hover:text-white">Subfolder A</a></li>
                    <li class="truncate"><a href="#" class="hover:text-white">Subfolder B</a></li>
                  </ul>
                </li>
              </ul>
            </li>
            <li>
              <ul class="leading-extra-loose pl-3">
                <li class="truncate"><a href="#" class="hover:text-white">Folder B</a>
                  <ul class="pl-3">
                    <li class="truncate"><a href="#" class="hover:text-white">Subfolder A</a></li>
                    <li class="truncate"><a href="#" class="hover:text-white">Subfolder B</a></li>
                  </ul>
                </li>
              </ul>
            </li>

          </ul>
        </div>
        <!-- FILES FOOTER -->
        <div class="bg-gray-600 h-16 px-4 py-2 flex items-center group">
          <svg class="fill-current text-gray-600 w-8 h-8 group-hover:text-white" viewBox="0 0 24 24" width="24" height="24"><path class="heroicon-ui" d="M12 22a10 10 0 110-20 10 10 0 010 20zm0-2a8 8 0 100-16 8 8 0 000 16zm1-9h2a1 1 0 010 2h-2v2a1 1 0 01-2 0v-2H9a1 1 0 010-2h2V9a1 1 0 012 0v2z"/></svg>
          <a href="#" class="font-normal text-gray-500 ml-2 group-hover:text-white">New Playlist</a>
        </div>
      </div>

      <!-- CONTENT WRAPPER -->
      <div class="bg-gray-800 flex-1 flex flex-col text-white">
        <!-- CONTENT HEADER -->
        <div class="top-bar flex items-center justify-between px-4 py-2">
         tesdt
        </div>
        <!-- CONTENT MAIN -->
        <div class="content overflow-y-auto h-full">
            <div class="editor-field h-full p-5" contentEditable="true">
              CONTENT EDITOR
            </div>
        </div>
      </div>
    </div>
    <!-- FOOTER -->
    <div class="bg-gray-700-spotify flex-none h-22 px-5 flex items-center justify-between">
      Footer Content
    </div>
  </div>
</template>

<script>
  import SystemInformation from './LandingPage/SystemInformation'

  export default {
    name: 'landing-page',
    components: { SystemInformation },
    methods: {
      open (link) {
        this.$electron.shell.openExternal(link)
      }
    }
  }
</script>

<style>

  .editor-field{
    height: 100%;
    outline: 0;
    border: 0;
    color: #00daff;
  }

</style>
