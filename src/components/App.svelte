<script>
  import Header from './Header.svelte'
  import Footer from './Footer.svelte'
  import Main from './Main.svelte'
</script>

<style>
  .siteWrapper {
    min-height: calc(100vh - 40px);
  }
  
  .footerBar {
    color: #8a8a8a;
    font-size: 12px;
    height: 40px;
    text-align: center;
  }
</style>

<div class="siteWrapper">
  <Header/>
  <Main/>
</div>
<div class="footerBar">
  <Footer/>
</div>