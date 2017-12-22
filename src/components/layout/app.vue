<script>
import RootHeader from './header/header'
import RootFooter from './footer/footer'
import SibebarLeft from './sidebar/left'
import SibebarRight from './sidebar/right'

export default {
  name: 'app',
  components: {
    RootHeader,
    RootFooter,
    SibebarLeft,
    SibebarRight
  }
}
</script>


<template>
  <div id="app" class="wrapper">
    <root-header />
    <sibebar-left />
    <router-view/>
    <root-footer></root-footer>
    <sibebar-right />
    <div class="control-sidebar-bg"></div>
  </div>
</template>
