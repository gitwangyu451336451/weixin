 <template>
  <div id="home">
      <home-header></home-header>
      <home-collection></home-collection>
      <home-news></home-news>
  </div>
</template>

<script>
import header from './header'
import collection from './myCollection'
import news from './news1'
export default {
  name: 'app',
  data () {
    return {
    }
  },
  components:{
      'home-header':header,
      'home-collection':collection,
      'home-news':news
  }
}
</script>

<style>
   #home{
       max-width:50em;
       margin: auto;
       background-color:#f0f1f5; 
   }
   h4{
        margin: 0em;
    }
   .title{
        padding:.5em;
        text-align: left;
    }
   .title h4{
        position: relative;
        margin-left: 1.25em;
    }
   .title h4::before{
        content: "";
        position: absolute;
        left: -.6125em;
        width:.3em;
        height:1em;
        background: linear-gradient(#52b3fa , #2097e9);
        border-radius: .15em;
    }
</style>
