<template>
  <div id="app">
    <!-- Content -->
    <div id="content">
      <div class="inner">
        <!-- Post -->
        <article class="box post post-excerpt">
          <header>
            <!--
									Note: Titles and subtitles will wrap automatically when necessary, so don't worry
									if they get too long. You can also remove the <p> entirely if you don't
									need a subtitle.
            -->
            <h2>
              <a href="#">Welcome to Mystery Science Theater 3000 Database</a>
            </h2>
            <p>This is a collection of all available MST3K episodes available online</p>
          </header>
        </article>
      </div>
    </div>
    <router-view />
  </div>
</template>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #ffffff;
}

#nav a.router-link-exact-active {
  color: #f5de11;
} */
</style>
