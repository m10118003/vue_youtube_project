<template>
  <header>
    <!-- Nav position -->
    <nav
      class="flex h-16 justify-between border border-black-600 items-center bg-white text-gray-800 px-5 py-3 text-sm fixed top-0 left-0 right-0 z-10">
      <div class="text-md flex items-center">
        <p class="mt-20 px-5 text-md w-100"><svg class="style-scope ytd-topbar-logo-renderer" viewbox="0 0 200 60"
            preserveaspectratio="xMidYMid meet" focusable="false"
            style="pointer-events: none; display: block; width: 100%; height: 100%;">
            <g class="style-scope ytd-topbar-logo-renderer" viewbox="0 0 200 60" preserveaspectratio="xMidYMid meet">
              <g class="style-scope ytd-topbar-logo-renderer">
                <path class="style-scope ytd-topbar-logo-renderer" fill="#FF0000"
                  d="M63,14.87c-0.72-2.7-2.85-4.83-5.56-5.56C52.54,8,32.88,8,32.88,8S13.23,8,8.32,9.31
                  c-2.7,0.72-4.83,2.85-5.56,5.56C1.45,19.77,1.45,30,1.45,30s0,10.23,1.31,15.13c0.72,2.7,2.85,4.83,5.56,5.56
                  C13.23,52,32.88,52,32.88,52s19.66,0,24.56-1.31c2.7-0.72,4.83-2.85,5.56-5.56C64.31,40.23,64.31,30,64.31,30
                  S64.31,19.77,63,14.87z">
                </path>
                <polygon class="style-scope ytd-topbar-logo-renderer" fill="#FFFFFF"
                  points="26.6,39.43 42.93,30 26.6,20.57"></polygon>
              </g>
              <g class="style-scope ytd-topbar-logo-renderer">
                <g class="style-scope ytd-topbar-logo-renderer" id="youtube-paths">
                  <path class="style-scope ytd-topbar-logo-renderer" fill="#282828"
                    d="M92.69,48.03c-1.24-0.84-2.13-2.14-2.65-3.91c-0.52-1.77-0.79-4.12-0.79-7.06v-4
                    c0-2.97,0.3-5.35,0.9-7.15c0.6-1.8,1.54-3.11,2.81-3.93c1.27-0.82,2.94-1.24,5.01-1.24c2.04,0,3.67,0.42,4.9,1.26
                    c1.23,0.84,2.13,2.15,2.7,3.93c0.57,1.78,0.85,4.16,0.85,7.12v4c0,2.94-0.28,5.3-0.83,7.08c-0.55,1.78-1.45,3.09-2.7,3.91
                    c-1.24,0.82-2.93,1.24-5.06,1.24C95.65,49.29,93.93,48.87,92.69,48.03z M99.66,43.71c0.34-0.9,0.52-2.37,0.52-4.4v-8.59
                    c0-1.98-0.17-3.42-0.52-4.34c-0.34-0.91-0.95-1.37-1.82-1.37c-0.84,0-1.43,0.46-1.78,1.37c-0.34,0.91-0.52,2.36-0.52,4.34v8.59
                    c0,2.04,0.16,3.51,0.49,4.4c0.33,0.9,0.93,1.35,1.8,1.35C98.71,45.06,99.31,44.61,99.66,43.71z">
                  </path>
                  <path class="style-scope ytd-topbar-logo-renderer" fill="#282828"
                    d="M188.16,37.13v1.39c0,1.77,0.05,3.09,0.16,3.98c0.1,0.88,0.32,1.53,0.65,1.93
                    c0.33,0.4,0.84,0.61,1.53,0.61c0.93,0,1.57-0.36,1.91-1.08c0.34-0.72,0.53-1.92,0.56-3.6l5.35,0.31
                    c0.03,0.24,0.04,0.57,0.04,0.99c0,2.55-0.7,4.45-2.09,5.71c-1.39,1.26-3.36,1.89-5.91,1.89c-3.06,0-5.2-0.96-6.43-2.88
                    c-1.23-1.92-1.84-4.88-1.84-8.9v-4.81c0-4.14,0.64-7.15,1.91-9.06c1.27-1.9,3.45-2.85,6.54-2.85c2.13,0,3.76,0.39,4.9,1.17
                    c1.14,0.78,1.94,1.99,2.41,3.64c0.46,1.65,0.7,3.93,0.7,6.83v4.72H188.16z M188.95,25.53c-0.31,0.39-0.52,1.03-0.63,1.91
                    c-0.11,0.88-0.16,2.23-0.16,4.02v1.98h4.54v-1.98c0-1.77-0.06-3.11-0.18-4.02c-0.12-0.91-0.34-1.56-0.65-1.93
                    c-0.31-0.37-0.8-0.56-1.46-0.56C189.75,24.94,189.26,25.14,188.95,25.53z">
                  </path>
                  <path class="style-scope ytd-topbar-logo-renderer" fill="#282828"
                    d="M77.59,36.61l-7.06-25.49h6.16l2.47,11.55c0.63,2.85,1.09,5.27,1.39,7.28h0.18
                    c0.21-1.44,0.67-3.85,1.39-7.24l2.56-11.6h6.16L83.7,36.61v12.23h-6.11V36.61z">
                  </path>
                  <path class="style-scope ytd-topbar-logo-renderer" fill="#282828"
                    d="M126.45,21.28v27.55h-4.85l-0.54-3.37h-0.13c-1.32,2.55-3.3,3.82-5.93,3.82c-1.83,0-3.18-0.6-4.05-1.8
                    c-0.87-1.2-1.3-3.07-1.3-5.62V21.28h6.2v20.23c0,1.23,0.13,2.11,0.4,2.63c0.27,0.52,0.72,0.79,1.35,0.79
                    c0.54,0,1.06-0.16,1.55-0.49c0.49-0.33,0.86-0.75,1.1-1.26V21.28H126.45z">
                  </path>
                  <path class="style-scope ytd-topbar-logo-renderer" fill="#282828"
                    d="M158.27,21.28v27.55h-4.85l-0.54-3.37h-0.13c-1.32,2.55-3.3,3.82-5.93,3.82c-1.83,0-3.18-0.6-4.05-1.8
                    c-0.87-1.2-1.3-3.07-1.3-5.62V21.28h6.2v20.23c0,1.23,0.13,2.11,0.4,2.63c0.27,0.52,0.72,0.79,1.35,0.79
                    c0.54,0,1.06-0.16,1.55-0.49c0.49-0.33,0.86-0.75,1.1-1.26V21.28H158.27z">
                  </path>
                  <path class="style-scope ytd-topbar-logo-renderer" fill="#282828"
                    d="M143.31,16.11h-6.16v32.72h-6.07V16.11h-6.16v-4.99h18.38V16.11z"></path>
                  <path class="style-scope ytd-topbar-logo-renderer" fill="#282828"
                    d="M178.8,25.69c-0.38-1.74-0.98-3-1.82-3.78c-0.84-0.78-1.99-1.17-3.46-1.17c-1.14,0-2.2,0.32-3.19,0.97
                    c-0.99,0.64-1.75,1.49-2.29,2.54h-0.05l0-14.52h-5.98v39.11h5.12l0.63-2.61h0.13c0.48,0.93,1.2,1.66,2.16,2.2
                    c0.96,0.54,2.02,0.81,3.19,0.81c2.1,0,3.64-0.97,4.63-2.9c0.99-1.93,1.48-4.95,1.48-9.06v-4.36
                    C179.36,29.84,179.17,27.43,178.8,25.69z M173.11,36.93c0,2.01-0.08,3.58-0.25,4.72c-0.16,1.14-0.44,1.95-0.83,2.43
                    c-0.39,0.48-0.91,0.72-1.57,0.72c-0.51,0-0.98-0.12-1.42-0.36c-0.43-0.24-0.79-0.6-1.06-1.08V27.71
                    c0.21-0.75,0.57-1.36,1.08-1.84c0.51-0.48,1.06-0.72,1.66-0.72c0.63,0,1.12,0.25,1.46,0.74c0.34,0.49,0.58,1.33,0.72,2.49
                    c0.13,1.17,0.2,2.83,0.2,4.99V36.93z">
                  </path>
                </g>
              </g>
            </g>
          </svg>
        </p>
      </div>
      <div class="text-md flex items-center">
        <a href="#">
          <svg
            class="fill-current mx-2 h-6 w-6 cursor-pointer text-gray-600" fill="none" viewbox="0 0 24 24" version="1.1"
            xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
            <g id="Page-1" stroke="currentColor" stroke-width="2" fill="none" fill-rule="evenodd">
              <g id="icon-shape">
                <path id="Combined-Shape" stroke-linecap="round" stroke-linejoin="round"
                  d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z">
                </path>
              </g>
            </g>
          </svg>
        </a>
        <a class="bg-orange-900 rounded-full text-white w-8 h-8 flex items-center justify-center text-lg"
          href="#">S</a>
      </div>
    </nav>
    <!-- Buttons -->
    <div class="button_bar bg-white-100 border border-black-600 pt-20 py-2 flex justify-center items-center">
      <div class="space-x-2">
        <button class="bg-gray-800 text-gray-100 py-2 px-4 rounded-full">全部</button>
        <button class="bg-gray-200 text-gray-800 py-2 px-4 rounded-full">平台遊戲</button>
        <button class="bg-gray-200 text-gray-800 py-2 px-4 rounded-full">動畫</button>
        <button class="bg-gray-200 text-gray-800 py-2 px-4 rounded-full">手工藝</button>
        <button class="act_game bg-gray-200 text-gray-800 py-2 px-4 rounded-full">動作冒險遊戲</button>
        <button class="pet bg-gray-200 text-gray-800 py-2 px-4 rounded-full">寵物</button>
        <button class="music bg-gray-200 text-gray-800 py-2 px-4 rounded-full">音樂</button>
        <button class="cook bg-gray-200 text-gray-800 py-2 px-4 rounded-full">烹飪</button>
        <button class="art bg-gray-200 text-gray-800 py-2 px-4 rounded-full">視覺藝術</button>
        <button class="live bg-gray-200 text-gray-800 py-2 px-4 rounded-full">直播中</button>
        <button class="sport_game bg-gray-200 text-gray-800 py-2 px-4 rounded-full">運動電玩遊戲</button>
        <button class="upload bg-gray-200 text-gray-800 py-2 px-4 rounded-full">最新上傳</button>
        <button class="collection bg-gray-200 text-gray-800 py-2 px-4 rounded-full">合輯</button>
        <button class="saw bg-gray-200 text-gray-800 py-2 px-4 rounded-full">已觀看</button>
        <button class="wow bg-gray-200 text-gray-800 py-2 px-4 rounded-full">讓你耳目一新的影片</button>
      </div>
    </div>
  </header>
  <!-- TV wall 12x -->
  <main class="h-screen mt-10 ml-0 px-12 py-6 xl:px-40">
    <div class="flex flex-col border-b border-gray-300">
      <div class="flex flex-row flex-wrap">
        <div class="mr-1 my-2"><img src="https://i.imgur.com/Wj6ay3X.png">
          <p class="text-sm py-1">The Puss Suite </p>
          <p class="text-xs text-gray-600">Henry Jackman - Topic</p>
          <p class="text-xs text-gray-600">觀看次數：41萬次 &bull; 6 年前</p>
        </div>
        <div class="mr-1 my-2"><img src="https://i.imgur.com/VFFvlOd.png">
          <p class="text-sm py-1">【超譯！骸骨騎士大人異世界...</p>
          <p class="text-xs text-gray-600">Muse木棉花</p>
          <p class="text-xs text-gray-600">觀看次數：1.2萬次  &bull; 2 週前</p>
        </div>
        <div class="mr-1 my-2"><img src="https://i.imgur.com/f1hfbUk.png">
          <p class="text-sm py-1">半吊子科學家研究長生不老藥...</p>
          <p class="text-xs text-gray-600">Some creator</p>
          <p class="text-xs text-gray-600">觀看次數：6260次 &bull; 2 週前</p>
        </div>
        <div class="mr-1 my-2"><img src="https://i.imgur.com/rhu3GOc.png">
          <p class="text-sm py-1">【original animation MV】...</p>
          <p class="text-xs text-gray-600">Marine Ch. 宝鐘マリン</p>
          <p class="text-xs text-gray-600">觀看次數：107萬次 &bull; 18 小時前</p>
        </div>
        <div class="mr-1 my-2"><img src="https://i.imgur.com/rQVRmwS.png">
          <p class="text-sm py-1">Katana ZERO OST - Hit The Floor</p>
          <p class="text-xs text-gray-600">JdotSweapA</p>
          <p class="text-xs text-gray-600">觀看次數：144萬次 &bull; 3 年前</p>
        </div>
        <div class="mr-1 my-2"><img src="https://i.imgur.com/XnY8mLA.jpg">
          <p class="text-sm py-1">Pekora看到一位在Cos她的...</p>
          <p class="text-xs text-gray-600">山寨猫 Copy Cat</p>
          <p class="text-xs text-gray-600">觀看次數：1.1萬次 &bull; 4 小時前</p>
        </div>
        <div class="mr-1 my-2"><img src="https://i.imgur.com/WmssvNt.png">
          <p class="text-sm py-1">骸骨騎士大人異世界冒險中...</p>
          <p class="text-xs text-gray-600">Muse木棉花-TW</p>
          <p class="text-xs text-gray-600">觀看次數：12萬次 &bull; 4 天前</p>
        </div>
        <div class="mr-1 my-2"><img src="https://i.imgur.com/0h6RqT9.jpg">
          <p class="text-sm py-1">長達十四年的日本懸案，卻...</p>
          <p class="text-xs text-gray-600">X調查</p>
          <p class="text-xs text-gray-600">觀看次數：379萬次 &bull; 1 年前</p>
        </div>
        <div class="mr-1 my-2"><img src="https://i.imgur.com/JdsNcI3.jpg">
          <p class="text-sm py-1">Some title for the video</p>
          <p class="text-xs text-gray-600">Some creator</p>
          <p class="text-xs text-gray-600">555K views &bull; 4 months ago</p>
        </div>
        <div class="mr-1 my-2"><img src="https://i.imgur.com/1oZL4Ix.jpg">
          <p class="text-sm py-1">Some title for the video</p>
          <p class="text-xs text-gray-600">Some creator</p>
          <p class="text-xs text-gray-600">666K views &bull; 5 months ago</p>
        </div>
        <div class="mr-1 my-2"><img src="https://i.imgur.com/Rp24maO.png">
          <p class="text-sm py-1">Some title for the video</p>
          <p class="text-xs text-gray-600">Some creator</p>
          <p class="text-xs text-gray-600">100K views &bull; 6 months ago</p>
        </div>
        <div class="mr-1 my-2"><img src="https://i.imgur.com/QhIo6Tu.png">
          <p class="text-sm py-1">Some title for the video</p>
          <p class="text-xs text-gray-600">Some creator</p>
          <p class="text-xs text-gray-600">87K views &bull; 8 months ago</p>
        </div>
        <div class="mr-1 my-2"><img src="https://i.imgur.com/uFcV8Mn.jpg">
          <p class="text-sm py-1">Some title for the video</p>
          <p class="text-xs text-gray-600">Some creator</p>
          <p class="text-xs text-gray-600">78K views &bull; 9 months ago</p>
        </div>
        <div class="mr-1 my-2"><img src="https://i.imgur.com/vofEo89.png">
          <p class="text-sm py-1">Some title for the video</p>
          <p class="text-xs text-gray-600">Some creator</p>
          <p class="text-xs text-gray-600">426K views &bull; 10 months ago</p>
        </div>
      </div>
    </div>
  </main>
<!-- Footer and icons, texts. -->
  <footer class="flex h-16 w-auto justify-center border border-black-600 items-stretch bg-white text-gray-800 px-5 py-3 text-sm fixed bottom-0 left-0 right-0">
    <div class="text-md flex items-center m-5 space-x-80 ">
      <a href="" target="_blank" rel="noreferrer" aria-label="Dribble" class="hover:opacity-75">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
          <path d="M10.707 2.293a1 1 0 00-1.414 0l-7 7a1 1 0 001.414 1.414L4 10.414V17a1 1 0 001 1h2a1 1 0 001-1v-2a1 1 0 011-1h2a1 1 0 011 1v2a1 1 0 001 1h2a1 1 0 001-1v-6.586l.293.293a1 1 0 001.414-1.414l-7-7z" />
        </svg>
        Home
      </a>
      <a href="" target="_blank" rel="noreferrer" aria-label="Dribble" class="hover:opacity-75">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
          <path stroke-linecap="round" stroke-linejoin="round" d="M17.657 18.657A8 8 0 016.343 7.343S7 9 9 10c0-2 .5-5 2.986-7C14 5 16.09 5.777 17.656 7.343A7.975 7.975 0 0120 13a7.975 7.975 0 01-2.343 5.657z" />
          <path stroke-linecap="round" stroke-linejoin="round" d="M9.879 16.121A3 3 0 1012.015 11L11 14H9c0 .768.293 1.536.879 2.121z" />
        </svg>
        Trending
      </a>
      <a href="" target="_blank" rel="noreferrer" aria-label="Dribble" class="hover:opacity-75">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
          <path stroke-linecap="round" stroke-linejoin="round" d="M9 13h6m-3-3v6m-9 1V7a2 2 0 012-2h6l2 2h6a2 2 0 012 2v8a2 2 0 01-2 2H5a2 2 0 01-2-2z" />
        </svg>
        Subscription
      </a>
      <a href="" target="_blank" rel="noreferrer" aria-label="Dribble" class="hover:opacity-75">
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-collection-play" viewBox="0 0 16 16">
          <path d="M2 3a.5.5 0 0 0 .5.5h11a.5.5 0 0 0 0-1h-11A.5.5 0 0 0 2 3zm2-2a.5.5 0 0 0 .5.5h7a.5.5 0 0 0 0-1h-7A.5.5 0 0 0 4 1zm2.765 5.576A.5.5 0 0 0 6 7v5a.5.5 0 0 0 .765.424l4-2.5a.5.5 0 0 0 0-.848l-4-2.5z"/>
          <path d="M1.5 14.5A1.5 1.5 0 0 1 0 13V6a1.5 1.5 0 0 1 1.5-1.5h13A1.5 1.5 0 0 1 16 6v7a1.5 1.5 0 0 1-1.5 1.5h-13zm13-1a.5.5 0 0 0 .5-.5V6a.5.5 0 0 0-.5-.5h-13A.5.5 0 0 0 1 6v7a.5.5 0 0 0 .5.5h13z"/>
        </svg>
        Library
      </a>
    </div>
  </footer>
</template>

<style lang="scss">
* {
  box-sizing: border-box;
  scroll-behavior: smooth;
}
// Make the total height and width of the elements includes padding and borders.
html,
body {
  height: 100%;
  margin: 0;
  padding: 0;
  overflow: hidden;
  // Make the layout default.
}
// Nav
nav {
  .bg-orange-900 {
    background-color: #816258;
  }
}
// button_bar
.button_bar {
  overflow: hidden;
}

// button_bar 1280px RWD
@media screen and (max-width: 1280px) {
  .button_bar {
    .saw {
      display: none;
    }
    .wow {
      display: none;
    }
  }
}
// button_bar 1024px RWD
@media screen and (max-width: 1024px) {
  .button_bar {
    .sport_game {
      display: none;
    }
    .upload {
      display: none;
    }
    .collection {
      display: none;
    }
  }
}
// button_bar 768px RWD
@media screen and (max-width: 768px) {
  .button_bar {
    .art {
      display: none;
    }
    .live {
      display: none;
    }
  }
}
// button_bar 375px RWD
@media screen and (max-width: 375px) {
  .button_bar {
    .act_game {
      display: none;
    }
    .pet {
      display: none;
    }
    .music {
      display: none;
    }
    .cook {
      display: none;
    }
  }
}
</style>
