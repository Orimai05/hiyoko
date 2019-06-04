<template>
  <div id="app">
    <!-- ヘッダーなどどのページでも表示するものはこのファイルに書く -->
    <app-header></app-header>
  <!-- ここに今表示しているコンポーネントが入る -->
    <router-view></router-view>
  </div>
</template>
<script>
import AppHeader from './components/AppHeader'
import TopPage from './components/TopPage'
import register from './components/register'


export default {
  name: 'app',
  components: {
    AppHeader,
    TopPage,
    register
  }
}
</script>
