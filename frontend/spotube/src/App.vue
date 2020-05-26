<template>
  <div class="app-container">
      <app-header></app-header> <br>
          <app-result></app-result>
      <app-footer></app-footer>
  </div>
</template>

<script>
import Header from './components/common/Header'
import Footer from './components/common/Footer'
import Result from './components/result/Result'

export default {
  components : {
    appHeader: Header,
    appFooter: Footer,
    appResult: Result
  },
  data () {
    return {
    }
  }
}
</script>

<style lang="scss">
.app-container{
      display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 10px 30px;
}

</style>
