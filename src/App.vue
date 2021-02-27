<template>
  <div>

    <nav class="navbar navbar-expand-lg navbar-light" id="main-nav">
      <a class="navbar-brand" href="/">ふじむらピアノ教室</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item">
            <router-link to="/" class="nav-link">ホーム</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/about" class="nav-link">講師紹介</router-link>
          </li>
        </ul>
      </div>
    </nav>

    <router-view></router-view>
    
  </div>
</template>

<script>
export default {}
</script>
