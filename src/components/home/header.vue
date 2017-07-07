 <template>
    <div class="header">
        <div class="logo">
            <img src="../../assets/home_logo.png"/>
        </div>
        <Swipe class="my-swipe">
            <SwipeItem class="slide1"></SwipeItem>
            <SwipeItem class="slide2"></SwipeItem>
            <SwipeItem class="slide3"></SwipeItem>
        </Swipe>
      
    </div>
</template>

<script>
import { Swipe, SwipeItem } from 'vue-swipe';
export default {
  name: 'app',
  data () {
    return {
      message: false
    }
  },
  methods:{
      getMessage(){
          this.message = true;
      }
  },
  created(){
      this.getMessage();
  },
  components:{
      'Swipe':Swipe,
      'SwipeItem':SwipeItem
  }
}
</script>

<style>
   
   .header{
       width: 100%;
       background: #ffffff;
   }
   .logo{
       position:relative;
       text-align: left;
       height:2.75em;
       
       max-height: 6.8em;
    }
   .logo img{
       position: absolute;
       top:50%;
       margin-left:.6em;
       width:60%;
       transform: translate(0,-50%);
   }
    .my-swipe {
        height: 8.875em;
        color: #fff;
        font-size: 16px;
        text-align: center;
    }

    .slide1 {
        background-color: #0089dc;
        color: #fff;
    }

    .slide2 {
        background-color: #ffd705;
        color: #000;
    }

    .slide3 {
        background-color: #ff2d4b;
        color: #fff;
    }
</style>
