<style scoped>
  /* pages/filedViewRecord/filedViewRecord.wxss */
  .mb10{
    margin-bottom:10px;
  }
  .oh{
    overflow: hidden;
    height:100%;
  }
  .flex {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
  }
  .flex-v {
    -webkit-box-orient: vertical;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }
  .flex-1 {
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
  }
  .body-view{
    width:100%;
    background:#fff;
    -webkit-box-sizing:border-box;
    box-sizing:border-box;
    padding:13px 15px 0;
  }
  .title{
    text-align:center;
  }
  .smlTitle{
    line-height:29px;
    font-size:16px;
    color:#222;
  }
  .bigTitle{
    line-height:27px;
    font-size:18px;
    color:#222;
  }
  .dashImg{
    height:2px;
    width:100%;
    margin:15px 0;
  }
  .dashImg2{
    height:2px;
    width:100%;
    margin:20px 0;
  }
  .textItem{
    line-height:22px;
    color:#333;
    font-size:15px;
  }
  .textItem2{
    line-height:33px;
    color:#999;
    font-size:14px;
  }
  .tableItem{
    border:1px solid #2eab3b;
    margin-top:-1px;
    line-height:16px;
    font-size:15px;
    color:#333;
    overflow:hidden;
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
  }
  .tableItem .tableItemLeft{
    padding:5px 0;
    display:inline-block;
    text-align:center;
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
  }
  .tableItem .tableItemRight{
    float:right;
    border-left:1px solid #2eab3b;
    width:77%;
    display:inline-block;
    text-align:center;
    -webkit-box-sizing:border-box;
    box-sizing:border-box;
    padding:9px 20px;
  }
  .tableItemCenter{
    line-height:43px;
    display:inline-block;
    text-align:center;
    width:100%;
    font-size:13px;
    color:#2eab3b;
    font-weight:700;
  }

  .signBox{
    width:100%;
    border:1px solid #2eab3b;
    -webkit-box-sizing:border-box;
    box-sizing:border-box;
    padding:12px 14px 11px;
  }
  .firstLine{
    padding:0 0;
    overflow:hidden;
    margin-bottom:18px;
  }
  .imgDiv{
    width:39px;
    align-items:center;
  }
  .imgDiv image{
    width:24px;
    height:24px;
  }
  .firstLineText{
    line-height:22px;
    font-size:14px;
    color:#333;
  }
  .secondLine{
    padding:0 0;
    overflow:hidden;
  }
  .secondLineText{
    line-height:22px;
    font-size:14px;
    color:#333;
  }
  .signShowBox{
    padding-top:15px;
    padding-bottom: 8px;

  }
  .openSignButton{
    display:block;
    width:40%;
    margin:0 auto;
    height:40px;
    text-align:center;
    line-height:40px;
    font-size:15px;
    color:#fff;
    background:#2eab3b;
    border-radius:15px;
  }
  .signedShowBox{
    padding-top:27px;
    height:100px;
  }
  .signedShowBox text{
    display:block;
    float: left;
    width:364px;
    text-align: right;
    font-size:15px;
    color:#222222;
    height: 88px;
    line-height: 88px;
  }
  .signedShowBox .signImg{
    width:88px;
    height: 260px;
    transform: rotate(-90deg) translate3d(-100%,0,0);
    transform-origin: left top;
  }

  .bottomTitleView{
    position:relative;
    margin-bottom:28px;
  }
  .bottomTitleBg{
    width:50%;
    height:16px;
    display:block;
    margin:0 auto;
  }
  .bottomTitleText{
    position:absolute;
    top:0;
    left:50%;
    transform:translate3d(-50%,0,0);
    height:16px;
    font-size:15px;
    color:#222;
    line-height:15px;
  }
  .bottomInfo{
    padding:0 13px 44px 34px;
  }
  .textItem3{
    line-height:22px;
    color:#666;
    font-size:13px;
    text-indent:-21px;
  }
  .red{
    color:#ff0000;
  }

  .signWrap{
    width: 100%;
    height: 100%;
    position: fixed;
    top: 0;
    left: 0;
    z-index: 10;
    background:rgba(0,0,0,0.8);
  }
  .signContent{
    position: absolute;
    left: 50%;
    top: 50%;
    transform:translate3d(-50%,-50%,0);
    background:#fff;
    width:90%;
    height: 80vh;
    border-radius:30px;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
    padding:17px 60px 0px 18px;
  }
  .signTip1{
    line-height: 40px;
    font-size:18px;
    right:37px;
    top:17px;
    color:#333333;
    width:100%;
    position: absolute;
    transform:rotate(90deg) translate3d(100%,0,0);
    transform-origin:right 50%;
  }
  .signHereBox{
    height:790px;
    width: 60%;
    border:1px solid #dedede;
    -webkit-border-radius: 10px;
    -moz-border-radius: 10px;
    border-radius: 10px;
    text-align: center;
    float: left;
  }
  .signHereTip{
    color:#e2e2e2;
    line-height: 234px;
    font-size:26px;
  }
  canvas{
    height:466px;
    width:100%;
    border-radius:20px;
    border:1px solid #ccc;
  }
  .closeBtn{
    background:#fff;
    position: absolute;
    right:-15px;
    bottom:-15px;
    width: 64px;
    height: 64px;
    -webkit-border-radius: 50%;
    -moz-border-radius: 50%;
    border-radius: 50%;
  }
  .closeBtn img{
    width: 26px;
    height: 26px;
    position: absolute;
    left:19px;
    top: 19px;
  }
  .signContentBottom{
    /*padding-top:12rpx;*/
  }
  .operationBox{
    width:50%;
    height: 116px;
    padding-top:17px;
    padding-left: 70px;
    display: flex;
  }
  .operationBox img{
    display: inline-block;
    width:54px;
    height: 54px;
    transform:rotate(90deg);
  }
  .confirmImg{
    margin-left: 28px;
  }
  .bbn{
    border-bottom:none;
  }
  #img-box,
  #canvas-drawImage h5, #canvas-brush {
    display: none;
  }
  #canvas-drawImage button{
    width: auto;
    position: absolute;
    flex: 1;
  }
  .wrap #control {
    width: 100%;
    height: auto;
    display: flex;
    flex-direction: row;
    text-align: center;
  }
  .fix-body {
    position: fixed !important;
    left: 0;
    top: 0;
    bottom: 0;
    right: 0;
    overflow: hidden;
  }
  .inner.draw {
    display: flex;
    flex-direction: row;
  }
  .draw h5 {
    margin-bottom: 10px;
  }
  #img-box {
    flex: 1;
    padding-left: 10px;
  }
  #img-box .img-item {
    position: relative;
    display: inline-block;
  }
  #img-box .img-item .fa {
    position: absolute;
    cursor: pointer;
    right: 1px;
    top: -1px;
    font-size: 12px;
    font-weight: 1;
    display: none;
    color: #ccc;
  }
  #img-box .img-item:hover .fa {
    display: block;
  }
  #img-box .img-item .fa:hover {
    color: #f2849e;
  }
  #img-box img {
    border: 1px #ccc solid;
    width: 90px;
    height: 60px;
    margin: 5px;
  }
  .wrap{
    width: 740px;
    border: 1px #585858 solid;
    overflow: hidden;
  }
  .fl{
    float: left;
    display: block;
  }
  #canvas{
    border-right: 1px #585858 solid;
    cursor: crosshair;
  }
  #control{
    width: 130px;
    height: 400px;
    margin-left: 4px;
  }
  #control div{
    padding: 5px;
  }
  #canvas-color ul{
    overflow: hidden;
    margin: 0;
    padding: 0;
  }
  #canvas-color ul li{
    float: left;
    display: inherit;
    width: 13px;
    height: 13px;
    border: 3px #fff solid;
    margin: 8px;
    cursor: pointer;
  }
  #canvas-color .active {
    border: 1px solid #f2849e;
  }
  #canvas-brush span{
    display: inline-block;
    width: 20px;
    height: 15px;
    margin-left: 10px;
    cursor: pointer;
  }
  #canvas-brush .small {
    font-size: 12px;
  }
  #canvas-brush .middle {
    font-size: 14px;
  }
  #canvas-brush .big {
    font-size: 16px;
  }

  #canvas-control span{
    display: inline-block;
    font-size: 14px;
    width: 20px;
    height: 15px;
    margin-left: 10px;
    cursor: pointer;
  }
  #canvas-control .active,
  #canvas-brush .active {
    color: #f2849e;
  }
  .drawImage {
    width: 100px;
    height: 30px;
    font-size: 12px;
    line-height: 30px;
  }
</style>
<template>
  <div style="background: #fff;">

    <!--<div class="body-view {{showSignFlag?'oh':''}}">-->
    <div class="body-view">
      <div class="title">
        <span class="smlTitle">{{detailData.insureName}}</span>
      </div>
      <div class="title">
        <span class="bigTitle">机动车辆保险事故现场查勘记录</span>
      </div>

      <img class="dashImg" style="width:100%;height:2px;" src="../images/dashline.png" />

      <div class="textItem">
        <span>报案号：{{detailData.reportNo}}</span>
      </div>
      <div class="textItem">
        <span>出险时间：{{detailData.accidentTime}}</span>
      </div>
      <div class="textItem mb10">
        <span>出险/查勘地点：{{detailData.accidentAddress}}</span>
      </div>
      <div class="textItem2">
        <span>保险车辆信息</span>
      </div>
      <div class="tableItem bbn">
        <span class="tableItemLeft">车牌号</span><span class="tableItemRight">{{targetVehicle.licenseNo}}</span>
      </div>
      <div class="tableItem bbn">
        <span class="tableItemLeft">驾驶员姓名</span><span class="tableItemRight">{{targetVehicle.casePerson}}</span>
      </div>
      <div class="tableItem bbn">
        <span class="tableItemLeft">联系方式</span><span class="tableItemRight">{{targetVehicle.phone}}</span>
      </div>
      <div class="tableItem bbn">
        <span class="tableItemLeft">保险公司</span><span class="tableItemRight">{{targetVehicle.companyName}}</span>
      </div>
      <div class="tableItem mb10">
        <span class="tableItemCenter" @click="gotolink('photoButton0',targetVehicle.licenseNo)" data-licenseNo="detailData.targetVehicle.licenseNo" id="">现场照片 ></span>
      </div>

      <div  v-for='(item,index) in thirdPartyList'>
        <div>
          <span class="textItem2">三者车辆信息</span>
        </div>
        <div class="tableItem bbn">
          <span class="tableItemLeft">车牌号</span><span class="tableItemRight">{{item.licenseNo}}</span>
        </div>
        <div class="tableItem bbn">
          <span class="tableItemLeft">联系方式</span><span class="tableItemRight">{{item.phone}}</span>
        </div>
        <div class="tableItem mb10">
          <span class="tableItemCenter" data-licenseNo="item.licenseNo" @click="gotolink('photoButton'+index+1,item.licenseNo)" >现场照片 ></span>
        </div>
      </div>
      <div class="textItem2">
          <span>被保险人（驾驶人）签字</span>
      </div>

      <!--签名框-->
     <div class="signBox">
          <div class="firstLine flex">
              <div class="imgDiv flex">
                  <img style="height:30px;width: 30px;" class="img flex" src="../images/greenCircle.png">
              </div>
              <div class="firstLineText flex-1">
                  <span>被保险人/驾驶人声明：以上内容本人确认属实；向你公司提交的索赔资料真实、可靠，没有任何 虚假和隐瞒；如有虚假、欺诈行为、愿意承担由此产生的所有法律责任。</span>
              </div>
          </div>
          <div class="secondLine flex">
              <div class="imgDiv flex">
                  <img style="height:30px;width: 30px;" @click="changeAgreeThird" v-if="agreeThird == 0" class="img flex" src="../images/greyCircle.png"/>
                  <img style="height:30px;width: 30px;" @click="changeAgreeThird" v-if="agreeThird == 1" class="img flex" src="../images/greenCircle.png"/>
              </div>
              <div class="secondLineText flex-1">
                  <span>被保险人同意由保险公司将此次事故造成三者车辆损失的赔款直接转至三者车提供的账户内。</span>
              </div>
          </div>
          <div class="signShowBox" v-if="signStatus==0?true:false">
              <span @click="showSignDiv" class="openSignButton">点击签字</span>
          </div>
          <div class="signedShowBox" v-if="signStatus!=0?true:false">
              <span>签字：</span>
            <img class="signImg" :src="signImgUrl">
          </div>
      </div>

      <img class="dashImg2" style="width:100%;height:2px;" src="../images/dashline.png" />

      <div class="bottomTitleView">
        <img class="bottomTitleBg" src="../images/titlebg.png" >
        <span class="bottomTitleText">理赔流程</span>
      </div>

      <div class="bottomInfo">
        <div class="textItem3">
          <span>1、前往就近或熟悉的修理厂（4s店）进行定损</span>
        </div>
        <div class="textItem3">
          <span>2、定损时拨打保险公司电话</span><span class="red">40001-88688</span><span>进行定损咨询</span>
        </div>
        <div class="textItem3">
          <span>3、确定事故损失后，出具机动车辆保险车辆损失情况确认书等索赔材料</span>
        </div>
        <div class="textItem3">
          <span>4、将索赔材料递交我司</span>
        </div>
        <div class="textItem3">
          <span>5、我司完成材料审核后，支付赔款。并在支付赔款后，进行通知及回访</span>
        </div>
        <div class="textItem3">
          <span>如有疑问可拨打：</span><span class="red">40001-88688</span><span>进行咨询</span>
        </div>
      </div>

    </div>

  </div>
</template>

<script>

  import axios from 'axios'
  export default {
    data() {
      return {
        val:true,
        url:"",
        username: "",
        valicode: "",
        userpwd: "",
        loginActive: false,
        detailData:{},
        targetVehicle: '',
        detailPhotoList:[],
        thirdPartyList:[],
        showSignFlag:false,
        context:null,
        signStatus:0,
        signImgUrl:'',
        agreeThird:0,
        surveyOrderNo:'',
        colors: ['#fef4ac','#0018ba','#ffc200','#f32f15','#cccccc','#5ab639'],
        brushs: [{
          className: 'small fa fa-paint-brush',
          lineWidth: 3
        },{
          className: 'middle fa fa-paint-brush',
          lineWidth: 6
        },{
          className: 'big fa fa-paint-brush',
          lineWidth: 12
        }],
        context: {},
        imgUrl: [],
        canvasMoveUse: true,
        preDrawAry: [],
        nextDrawAry: [],
        middleAry: [],

      }
    },
    created(){
      this.getDetailData();
    },
    mounted() {
    },
    watch: {

    },
    methods: {

      showSignDiv(){
        this.$router.push({path:'/signName'})

      },
      changeAgreeThird(){
        if(this.agreeThird == 0){
          this.agreeThird = 1

        }else{
          this.agreeThird = 0
        }
      },
      gotolink: function(id,licenseNo){
        var licenseNo = licenseNo;
        var idStr = String(id).replace('photoButton','');
        if(idStr=='0'){
          if(this.detailPhotoList.length == 0) {
            wx.showToast({
              title: '此车暂无照片',
              duration: 1500
            })
          }else{
            localStorage.setItem('showPhotoList',JSON.stringify(this.detailPhotoList));
            this.$router.push({path:'/photoList/'+licenseNo});
          }
        }else{
          idStr = Number(idStr)-1;
          if(this.thirdPartyList[idStr].photoList.length == 0){
            wx.showToast({
              title: '此车暂无照片',
              duration: 1500
            })
          }else{
            localStorage.setItem('showPhotoList',JSON.stringify(this.detailPhotoList));
            this.$router.push({path:'/photoList/'+licenseNo});
          }
        }
      },
      open2() {
        this.$message({
          message: '登陆成功',
          type: 'success'
        });
      },
      open4(resdes) {
        this.$message.error(resdes);
      },
      getDetailData(){
        var paramData = {
          'surveyNo': 'bac0f3489c764c7c84dc03a64b45a498'
        }
        axios.post(this.ajaxUrl+"/survey_detail/v1/getDetail",paramData)
          .then(response => {
            if(response.status == 200){
              this.detailData = response.data.detail;
              this.targetVehicle = response.data.targetVehicle;
              this.detailPhotoList = response.data.targetVehicle.photoList;
                this.thirdPartyList = response.data.thirdPartyList;
                this.signStatus = response.data.detail.signStatus;
                this.signImgUrl = response.data.detail.signUrl;
                this.agreeThird = response.data.detail.isAgreeThird;
            }
          }, err => {
            console.log(err);
          })
          .catch((error) => {
            console.log(error)
          })
      },
    },
    components: {
    },
  };
</script>

