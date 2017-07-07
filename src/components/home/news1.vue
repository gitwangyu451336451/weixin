 <template>
    <div id="news">
           <ul>
               <li>
                    <a class="title"><h4>学校通知</h4></a>
                    <a class="news_content">
                       <div>各位同学请注意！于今日下午14:00学院召开《夏季安全预防大会》请各位同学注意时间，尊师参加！会前会同意点名，无理由没来参加的同学会受到严厉的处罚。</div>
                           <div class="news_bm">
                               <span>教务处</span>
                               <span>
                                   <img src="../../assets/home_time.png"/>
                                   <span>16:30</span>
                               </span>
                           </div>
                    </a>
                    <a class="more">查看更多</a>
               </li>
               <li>
                    <a class="title"><h4>学校通知</h4></a>
                    <a class="news_content">
                       <div>各位同学请注意！于今日下午14:00学院召开《夏季安全预防大会》请各位同学注意时间，尊师参加！会前会同意点名，无理由没来参加的同学会受到严厉的处罚。</div>
                           <div class="news_bm">
                               <span>教务处</span>
                               <span>
                                   <img src="../../assets/home_time.png"/>
                                   <span>16:30</span>
                               </span>
                           </div>
                    </a>
                    <a class="more">查看更多</a>
               </li>
           </ul>
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
}
ul{
    list-style: none;
    text-align: left;
    padding:0em;
    margin: 0em;
}
ul li{
    margin-top:1em; 
    border-bottom: 1px solid #f2f2f2;
    background: white;
}
ul li a{
    display: block;
}
.news_content{
    font-size: 13px;
    color:#555555;
    border-top:1px solid #f2f2f2;
    padding: 0.923em;
}
.news_bm{
    text-align: right;
    font-size: 12px;
    height: 2em;
    line-height: 2em;
    
}
.news_bm span{
    display: inline-block;
    text-align: right;
    height: 1.2em;
    line-height: 1.2em;
    vertical-align: middle;
}
.news_bm span:first-child{
    border: 1px solid #008fff;
    color: #008fff;
    padding:0em .2em;
    border-radius: .2em;
}
.news_bm span:last-child{
    position: relative;
    padding:.1em .2em;
    width:3.5em;
    height: 1em;
    line-height: 1em;
    margin-left:1em;
    text-align: right;
}
.news_bm span:last-child img{
    position:absolute;
    height:80%;
    top:50%;
    left:0;
    transform: translate(0,-50%);
}
.news_bm span:last-child span{
    position:absolute;
    height:80%;
    top:50%;
    right: 0;
    transform: translate(0,-50%);
}
.more{
    font-size: 12px;
    text-align: center;
    height: 3em;
    line-height: 3em;
    color: #999999;
    background: #f9f9f9;
}
</style>
