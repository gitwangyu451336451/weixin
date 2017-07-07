 <template>
    <div id="collection">
      <div class="title">
          <h4>应用中心</h4>
      </div>
      <div class="content">
          <a href="www.baidu.com">
              <div>
                  <img src="../../assets/home_zhkt.png"/>
              </div>
              <div>
                  <span>智慧课堂</span>
              </div>
          </a>
          <a>
              <div>
                  <img src="../../assets/home_zhkt.png"/>
              </div>
              <div>
                  <span>智慧课堂</span>
              </div>
          </a>
           <a>
              <div>
                  <img src="../../assets/home_zhkt.png"/>
              </div>
              <div>
                  <span>智慧课堂</span>
              </div>
          </a>
           <a>
              <div>
                  <img src="../../assets/home_zhkt.png"/>
              </div>
              <div>
                  <span>智慧课堂</span>
              </div>
          </a>
           <a>
              <div>
                  <img src="../../assets/home_zhkt.png"/>
              </div>
              <div>
                  <span>智慧课堂</span>
              </div>
          </a>
          <div class="clear"></div>
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
#collection{
    margin-top:.6em;
    background: white;
}

.content{
    font-size: 14px;
    border-top:1px solid #f2f2f2;
}
.content > a{
    display: block;
    height:6.642em;
    width: calc(25% - 1px);
    border-right:1px solid #f2f2f2;
    border-bottom:1px solid #f2f2f2;
    float: left;
}
.content a div:first-child{
    width:1.875em;
    margin:1.25em auto 0.77em auto;
}
.content a div:last-child{
    padding-bottom: 1em;
    font-size:13px;
    font-family: "Ping-Fang-SC-Medium";
    color:#555555;
}
.content a div img{
    width:100%;
}
.clear{
    clear: both;
}
</style>
