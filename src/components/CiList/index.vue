<template>
   <div  class="cinema_body">
       <div  class="wrapper">
           <ul>
               <li>
                   <div> 
                       <span >喜洋时代影城(洛溪奥园店)</span>
                       <span  class="q"><span  class="price">22.9</span> 元起</span>
                   </div>
                   <div  class="address">
                       <span >番禺区洛浦街奥林匹克大厦四楼</span>
                       <span >1896.6km</span>
                   </div>
                   <div  class="card">
                       <div  class="or">折扣卡</div>
                       <div  class="or">小吃</div>
                       </div>
             </li>
             <li >
                 <div>
                     <span >中影天川国际影城(永泰店)</span>
                     <span  class="q"><span  class="price">23</span> 元起</span>
                 </div>
                 <div  class="address">
                     <span >白云区丛云路945号嘉福商业广场三楼</span>
                     <span >1877km</span>
                 </div>
                 <div  class="card">
                     <div  class="or">折扣卡</div>
                     <div  class="or">小吃</div>
                 </div>
             </li>
        </ul>
    </div>
 </div>
</template>

<script>
export default {
  name: "CiList"
};
</script>

<style scoped>
#content .cinema_body {
  -webkit-box-flex: 1;
  -ms-flex: 1;
  flex: 1;
  overflow: auto;
}
.cinema_body ul {
  padding: 20px;
}
.cinema_body li {
  border-bottom: 1px solid #e6e6e6;
  margin-bottom: 20px;
}
.cinema_body div {
  margin-bottom: 10px;
}
.cinema_body .q {
  font-size: 11px;
  color: #f03d37;
}
.cinema_body .price {
  font-size: 18px;
}
.cinema_body .address {
  font-size: 13px;
  color: #666;
}
.cinema_body .address span:nth-of-type(2) {
  float: right;
}
.cinema_body .card {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
}
.cinema_body .card div {
  padding: 0 3px;
  height: 15px;
  line-height: 15px;
  border-radius: 2px;
  color: #f90;
  border: 1px solid #f90;
  font-size: 13px;
  margin-right: 5px;
}
.cinema_body .card div.or {
  color: #f90;
  border: 1px solid #f90;
}
.cinema_body .card div.bl {
  color: #589daf;
  border: 1px solid #589daf;
}

</style>
