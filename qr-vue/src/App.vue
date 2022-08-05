<template>
  <div id="app">
    <header>
      <div class="container">
        <div class="header">
          <div class="header__logo section-h3">{{this.$route.name}}</div>
        </div>
      </div>
    </header>
    <main>
      <router-view/>
    </main>
    <div class="bottom-bar">
      <div class="container">
        <div class="bottom-bar__item">
          <div class="icon">
            <svg xmlns="http://www.w3.org/2000/svg" height="24" width="24"><path d="M9.575 13.425h10l-3.45-4.5-2.3 3-1.55-2Zm-.7 4.85q-1.325 0-2.237-.913-.913-.912-.913-2.237v-11.4q0-1.325.913-2.238Q7.55.575 8.875.575h11.4q1.325 0 2.238.912.912.913.912 2.238v11.4q0 1.325-.912 2.237-.913.913-2.238.913Zm0-3.15h11.4v-11.4h-11.4v11.4Zm-5.15 8.3q-1.325 0-2.237-.912-.913-.913-.913-2.238V5.725h3.15v14.55h14.55v3.15Zm5.15-19.7v11.4-11.4Z"/></svg>
          </div>
          <div class="name">From Image</div>
        </div>
        <div class="bottom-bar__item">
          <div class="icon">
            <svg xmlns="http://www.w3.org/2000/svg" height="24" width="24"><path d="M11.95 21.85q-3.8 0-6.612-2.525Q2.525 16.8 2.175 13H5.35q.375 2.475 2.238 4.087Q9.45 18.7 11.95 18.7q2.8 0 4.75-1.95 1.95-1.95 1.95-4.75T16.7 7.25Q14.75 5.3 11.95 5.3q-1.425 0-2.725.587-1.3.588-2.25 1.688h2.05V10H2.35V3.375h2.375V5.35q1.4-1.55 3.263-2.375Q9.85 2.15 11.95 2.15q2.025 0 3.825.775 1.8.775 3.138 2.112 1.337 1.338 2.112 3.138.775 1.8.775 3.825 0 2.025-.775 3.825-.775 1.8-2.112 3.137-1.338 1.338-3.138 2.113-1.8.775-3.825.775Zm2.675-5.45-3.8-3.8V7H13.2v4.6l3.125 3.1Z"/></svg>
          </div>
          <div class="name">
            History
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
@import "styles/main.scss";
</style>
