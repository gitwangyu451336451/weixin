 <template>
    <div id="news">
       <div class="news_header">
           新闻资讯
       </div>
       <div class="news_list">
           <ul>
               <li>
                   <a>
                       <span>本公司参加第十八届广州商品</span>
                       <span>2017-07-06</span>
                   </a>
               </li>
               <li>
                   <a>
                       <span>本公司参加第十八届广州商品</span>
                       <span>2017-07-06</span>
                   </a>
               </li>
               <li>
                   <a>
                       <span>本公司参加第十八届广州商品</span>
                       <span>2017-07-06</span>
                   </a>
               </li>
               <li>
                   <a>
                       <span>本公司参加第十八届广州商品</span>
                       <span>2017-07-06</span>
                   </a>
               </li>
           </ul>
       </div>
    </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
     
    }
  },
  methods:{
    
  },
  created(){
     
  }
}
</script>

<style>
#news{
    margin-top:.6em;
    background: white;
}
.news_header{
    height:1.6875em;
    line-height: 1.6875em;
    padding: .5em;
    background: url('../../assets/home_news_logo.png');
    color: white;
    background-clip:padding-box;
    background-size: cover;
    background-repeat:no-repeat;
    outline: 1px solid white;
    outline-offset: -.6em;
}
.news_header div::before{
    content: "";
    
}
.news_header img{
    width:100%;
}
ul{
    list-style: none;
    text-align: left;
    padding:0em;
    margin: 0em;
}
ul li{
    border-bottom: 1px solid #f2f2f2;
    padding:1em 0em;
}
ul li a{
    display: flex;
}
ul li a span:first-child{
    flex: 3;
}
ul li a span:last-child{
    flex: 1;
}
.news_list{
    padding: .5em;
    font-size: 14px;
}
</style>
