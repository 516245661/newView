<style scoped>
	.index-page{
		background-color: #fff;
		min-width:1200px ;
	}
	.modul-one{
		position: relative;
		text-align: center;
		height: 848px;
		background:url('../images/unlogin/bg/guide.png') center no-repeat #0b0e1f;
		overflow: hidden;
	}
	#div1{
		position: relative;
	    width: 450px;
        height: 150px;
	    margin: auto;
	}
	#div1 a{
		position: absolute;
	    top: 0px;
	    left: 0px;
	    font-family: Microsoft YaHei;
	    color: #fff;
	    font-weight: 400;
	    text-decoration: none;
	    padding: 3px 8px;
	}
	.modul-one-position1{
	    position: absolute;
	    top: 60px;
	    left:-moz-calc(50% - 242px);
	    left:-webkit-calc(50% - 242px); 
	    left: calc(50% - 242px);
	}
	.modul-one-position2{
		position: absolute;
	    bottom: 90px;
	    left:-moz-calc(50% - 207px);
	    left:-webkit-calc(50% - 207px); 
	    left: calc(50% - 207px);
		font-size: 82px; 
		color: #0e86dc; 
		font-family: 微软雅黑; 
		letter-spacing: 1px; 
		font-weight: bold;
	}
	.modul-one-position3{
		position: absolute;
	   	bottom: 50px;
	    left:-moz-calc(50% - 250px);
	    left:-webkit-calc(50% - 250px); 
	    left: calc(50% - 250px);
		font-size: 33px;
		color: #ececed; 
		font-family: 微软雅黑; 
		letter-spacing: 6px;
	}
	.modul-one-position4{
		position: absolute;
	   	bottom: 15px;
	    left:-moz-calc(50% - 20px);
	    left:-webkit-calc(50% - 20px); 
	    left: calc(50% - 20px);
	}
	.module-two{
	    position: relative;
	    display: flex;
	    justify-content: center;
	    align-items: center;
	    flex-wrap: wrap;
	}
	.module-two>img{
		position: absolute;
		left: 0;
	}
	.module-two-content{
		position: relative;
		margin-top: 130px;
		box-shadow: 0 0 27px rgba(8, 8, 8, 0.13);
		width: 950px;
		height: 450px;
	}
	.one-ing{
		position: absolute;
	    bottom: 40px;
    	left: -40px;
	}
	.two-ing{
		position: absolute;
		top: -80px;
    	left: 305px;
	}
	.three-ing{
		position: absolute;
	    bottom: -40px;
    	right: -40px;
	}
	.four-ing{
		position: absolute;
	    left: 350px;
    	top: -100px;
	}
	.module-two-p{
		width: 950px;
		margin: 70px auto;
		font-size: 35px;
		text-align: right;
	    color: #787878;
	}
	.module-three{
		background-image:url('../images/unlogin/bg/bginteMark.png') ;
	}
	.module-three-head{
		color: #fff;
		text-align: center;
		padding-top:100px ;
		padding-bottom: 20px;
	}
	.module-three-content{
		width: 1100px;
		margin: auto;
		display: flex;
		flex-wrap:wrap ;
		justify-content: center;
	}
	.module-three-content .spans{
	    display: flex;
    	align-items: flex-end;
	    width: 220px;
	    height: 220px;
	    color: #ffffff;
	    font-size: 21px;
	    font-family: "微软雅黑";
	    font-weight: bold;
	    justify-content: center;
	    margin: 10px;
        padding-bottom: 35px;
	}
	.module-three-content .span1{
		background: url('../images/unlogin/bg/icon.png')no-repeat #4874e9;
		background-position:65px 65px;
	}
	.module-three-content .span2{
		background: url('../images/unlogin/bg/icon.png')no-repeat #333949;
		background-position:-155px 65px;
	}
	.module-three-content .span3{
		background: url('../images/unlogin/bg/icon.png')no-repeat #28c29a;
		background-position:-375px 65px;
	}
	.module-three-content .span4{
		background: url('../images/unlogin/bg/icon.png')no-repeat #333949;
		background-position:-595px 65px;
	}
	.module-three-content .span5{
		background: url('../images/unlogin/bg/icon.png')no-repeat #333949;
		background-position:65px -140px;
	}
	.module-three-content .span6{
		background: url('../images/unlogin/bg/icon.png')no-repeat #ff6d6a;
		background-position:-155px -140px;
	}
	.module-three-content .span7{
		background: url('../images/unlogin/bg/icon.png')no-repeat #333949;
		background-position:-375px -140px;
	}
	.module-three-content .span8{
		background: url('../images/unlogin/bg/icon.png')no-repeat #bc910b;
		background-position:-595px -140px;
	}
	.module-four{
		background: url('../images/unlogin/bg/cloud.png') repeat-x bottom #3e69dc;
		text-align: center;
	}
	.module-four p{
		margin: 0;
	}
	.module-four-top{
		position: relative;
		text-align: center;
		color: #FFF;
		margin-bottom: 30px;
	}
	.module-four-top p {
	    position: absolute;
	    bottom: -10px;
	    left:-moz-calc(50% - 180px);
	    left:-webkit-calc(50% - 180px); 
	    left: calc(50% - 180px);
	    font-size: 72px;
	    font-family: "宋体";
	}
	.module-four-img{
		position: relative;
		height: 600px;
	}
	.module-four-img .one-img{
	    position: absolute;
	    left:-moz-calc(50% - 205px);
	    left:-webkit-calc(50% - 205px); 
   	 	left: calc(50% - 205px);
	    top: 20px;
	}
	.module-four-img .two-img{
	    position: absolute;
	    left:-moz-calc(50% - 433px);
	    left:-webkit-calc(50% - 433px); 
   	 	left: calc(50% - 433px);
	    top: 70px;
	}
	.text-align-center{
		text-align: center;
	}
	.module-five{
		text-align: center;
		background: #f6f6f6;
		padding: 80px 0 60px;
	}
	.module-six{	
		color: #fff;
		background: #2c313f;
		padding: 40px;
		position: relative;
	}
	.module-six-showbox {
		width: 1200px; margin: 0 auto; overflow: hidden; position: relative; height: 428px;
	}
	.pre{
	    position: absolute;
	    left: 0;
        top: 60%;
		width: 70px;
		height:70px;
		background: url('../images/unlogin/bg/arrows.png')no-repeat;
		background-position:0 0;
	}
	.next{
		position: absolute;
		right: 0;
		width: 70px;
		height:70px;
		top: 60%;
		background: url('../images/unlogin/bg/arrows.png')no-repeat;
		background-position:34% 0
	}
	.caseImg{
		overflow: hidden;
		width: 9100px; 
		margin: 10% 0 0 0; 
		position: absolute; 
		left: -340px;
		top: 0;
	}
	.caseImg li{
		margin: 0.4em;
		float: left;
		width: 290px; 
		height: 290px;
		background: #FFFFFF; 
		line-height: 290px; 
		overflow: hidden;
	}
	.caseImg a{
		display: block;
		color: #b2b3b6; 
		line-height: 438px; 
		text-align: center;
	}
	.caseImg .ani{
		background: #FFFFFF;
	}
	.caseImg .intr{
		font-size: 18px; margin-top: 7%;
	}
	.caseImg .intrMain{
		font-size: 11px;margin-top: 4%; text-align: left;
	}
	.caseImg img{
		margin: 0 0 0 0; width: 290px;
	}
	.synopsis li{
		width: 290px;
	}
	.module-seven{
		background: #f6f6f6;
		padding-bottom: 60px;
	}
	.module-seven-img{
		text-align: center;
		padding: 60px 0 20px;
	}
	.module-seven-content{
		width: 1000px;
		margin: auto;
		padding: 20px 50px 40px;
	    border: 2px solid #cacaca;
	}
	.module-seven-content ol li{
		list-style-type: decimal;
		font-size: 25px;
	}
	img{
		max-width: 100%;
	}
	a{
		cursor: pointer;
	}
</style>
<template>
	<div class="index-page">
		<div class="module modul-one">
			<div id="div1">
				<a>自助选档</a> <a>  送礼</a> <a> 优惠券</a> <a>  方案支持 </a> <a> 众筹</a> <a> 拒绝雷同 </a> <a>  分销</a> <a>自助选档</a> <a> 营销工具 </a> <a> 离店管理 </a> <a>  补贴</a> <a>  APP</a> <a>自助选档</a> <a>  送礼</a> <a> 优惠券</a> <a>  方案支持 </a> <a> 众筹</a> <a> 拒绝雷同 </a> <a>  分销</a> <a>自助选档</a> <a> 营销工具 </a> <a> 离店管理 </a>
				<a>  补贴</a> <a>  APP</a> <a>  支付</a> <a>DIY </a> <a>流程管家</a> <a>返现</a> <a>  团购</a> <a>   补贴</a> <a> 众筹</a> <a> 拒绝雷同 </a> <a>  分销</a> <a>自助选档</a> <a> 营销工具 </a> <a> 离店管理 </a> <a>  补贴</a> <a>  APP</a> <a>  支付</a> <a>DIY </a> <a>流程管家</a> <a>返现</a> <a>  团购</a> <a>   补贴</a>
			</div>
			<div class="modul-one-position1"> <img src="../images/unlogin/bg/iphone.png"/> </div>
			<div class="modul-one-position2">卤蛋微商城</div>
			<div class="modul-one-position3">中国摄影行业微电商服务专家</div> 
			<div class="modul-one-position4"><img src="../images/unlogin/bg/downArr.png"/></div>
		</div>
		<div class="module module-two">
			<img src="../images/unlogin/bg/viua.png"/>
			<div class="module-two-content">
				<img class="one-ing" src="../images/unlogin/bg/creat.png"/>
				<img class="two-ing" src="../images/unlogin/bg/iphone2.png"/>
				<img class="three-ing" src="../images/unlogin/bg/diyde.png"/>
				<img class="four-ing" src="../images/unlogin/bg/label.png"/>
			</div>
			<div class="module-two-p">
				<p>无需编程，可视化拖拽制作页面 拒</p>
				<p>绝界面雷同，DIY秀出个性!</p>
			</div>
		</div>
		<div class="module module-three">
			<div class="module-three-head">
				<p style="font-size: 30px;">INTERACTIVE MARKETING</p>
				<p style="font-size: 90px;">互动营销</p>
			</div>
			<div class="module-three-content">
				<div class="spans span1">分销系统</div>
				<div class="spans span2">排空系统</div>
				<div class="spans span3">对接微信</div>
				<div class="spans span4">众筹系统</div>
				<div class="spans span5">我要送礼</div>
				<div class="spans span6">团购返现</div>
				<div class="spans span7">小游戏</div>
				<div class="spans span8">数据统计</div>
			</div>
			<div class="module-three-head" style="padding: 30px 0 70px 0;">
				<p style="font-size: 32px;">搭配互动营销工具让你的微商城更具传播性！ </p>
				<p style="font-size: 32px;">特色功能不断上新，都是神级辅助！</p>
			</div>
		</div>
		<div class="module module-four">
			<div class="module-four-top">
				<img src="../images/unlogin/bg/kuang.png"/>
				<p>/自助选档/</p>
			</div>
			<p style="font-size: 27px;color: #fff;">档期开放、预售数量都由你自由设置 客户</p>
			<p style="font-size: 27px;color: #fff;">在线自助选档就像电影选座一样简单!</p>
			<div class="module-four-img">
				<img class="one-img" src="../images/unlogin/bg/btn.png"/>
				<img class="two-img" src="../images/unlogin/bg/cloud2.png"/>
			</div>
			<p style="font-size: 72px;font-weight: bold;">流程管家</p>
			<p style="font-size: 30px;font-family: 宋体;">从订单到取件全程监管：拍摄流程安排、服务环节自动提醒，客户用手机即可</p>
			<p style="font-size: 30px;font-family: 宋体;">自助查询服务进度及下一步安排，支持在线评分，同时自动生成满意度榜单。</p>
			<p style="font-size: 30px;font-family: 宋体;">客户评价与满意度统计一箭双雕!</p>
		</div>
		<div class="text-align-center">
			<img src="../images/unlogin/bg/flowSte.png"/>
		</div>
		<div class="module module-five">
			<p style="font-size: 72px;">二销助手</p>
			<p style="font-size: 72px;">产品库</p>
			<p style="font-size: 32px;">手机拍摄，轻松上传，便捷管理二销产品</p>
			<p><img src="../images/unlogin/bg/icon2.png"/></p>
			<p style="font-size: 32px;">在线预览&nbsp;&nbsp;>&nbsp;&nbsp;勾选清单&nbsp;&nbsp;>&nbsp;&nbsp;自动结算&nbsp;&nbsp;>&nbsp;&nbsp; 二销收款&nbsp;&nbsp;</p>
		</div>
		<div class="module module-six">
			<p style="font-size: 42px;text-align: center;">客户案例</p>
			<a name="pre"><div class="pre"></div></a>
			<a><div class="next"></div></a>
			<div class="module-six-showbox">
				<ul class="caseImg">
					<li> <a style="line-height: 300px;" class="ani" ><img src="../images/unlogin/zchongqing1024LOGO.jpg"/></a> </li>
					<li> <a style="line-height: 300px;" class="ani" ><img src="../images/unlogin/zjingfurenLOGO.jpg"/></a> </li>
					<li> <a style="line-height: 300px;" class="ani" ><img src="../images/unlogin/zluodansheying.jpg"/></a> </li>
					<li> <a style="line-height: 300px;" class="ani" ><img src="../images/unlogin/zmishiLOGO.jpg"/></a> </li>
					<li> <a style="line-height: 300px;" class="ani" ><img src="../images/unlogin/zniuyueLOGO.jpg"/></a> </li>
					<li> <a style="line-height: 300px;" class="ani" ><img src="../images/unlogin/znongqingLOGO.jpg"/></a> </li>
					<li> <a style="line-height: 300px;" class="ani" ><img src="../images/unlogin/zshihuaLOGO.jpg"/></a> </li>
					<li> <a style="line-height: 300px;" class="ani" ><img src="../images/unlogin/ztianziLOGO.jpg"/></a> </li>
					<li> <a style="line-height: 300px;" class="ani" ><img src="../images/unlogin/zxinfuLOGO.jpg"/></a> </li>
					<li> <a style="line-height: 300px;" class="ani" ><img src="../images/unlogin/zxinyueLOGO.jpg"/></a> </li>
					<li> <a style="line-height: 300px;" class="ani" ><img src="../images/unlogin/zzhulil.jpg"/></a> </li>
				</ul>
			</div>
			
		</div>
		<div class="module module-seven">
			<div class="module-seven-img">
				<img src="../images/unlogin/bg/must.png"/>
			</div>
			<div class="module-seven-content">
				<ol>
					<li>卤蛋商城现阶段只面对企业用户开放注册，注册店铺时上传企业资质即可；</li>
					<li>卤蛋商城现阶段只接受推荐注册，您需要拥有推荐码方可成功注册；</li>
					<li>商户申请提现时会产生一定的手续费，此费用是由第三方支付公司收取的支付手续费。 为了给商户们提供更完善的服务，卤蛋商城将对该手续费进行全额补贴；</li>
					<li>卤蛋商城的营销工具和特色功能不定期升级和上新，都是神级辅助。</li>
				</ol>
			</div>
		</div>
	</div>
</template>
<script>
	import firstpage  from '../js/firstpage.js' 
	export default {
        data: () => ({
        	radius : 560,
			d:1000,
			mcList : [],
			active : false,
			lasta : 1,
			lastb : 1,
			distr : true,
			tspeed:10,
			size:250,
			mouseX:0,
			mouseY:0,
			howElliptical:300,
			aA:null,
			oDiv:null,
			sa:'' ,
			ca:'' ,
			sb:'' ,
			cb:''  ,
			sc:''  ,
			cc:'' ,
        }),
        created() {
        	
        },
        ready() {
        	this.stat();//轮播
        	this.onload();
        },
        methods: {
        	stat(){
        		let timer=null;
				let auto=function(){
					timer=setInterval(function(){
						$(".caseImg").animate({'left':-40},500,function(){
							$(".caseImg").css('left','-340px');
							$(".caseImg li:last").insertBefore(".caseImg li:first");
						})
					},2500);
				};
				auto()
				$(".module-six-showbox").hover(function(){
					clearInterval(timer)
				},function(){
					timer=setInterval(function(){
						$(".caseImg").animate({'left':-40},500,function(){
							$(".caseImg").css('left','-340px');
							$(".caseImg li:last").insertBefore(".caseImg li:first");
						})
					},2500);
				});
				$(".pre").stop().click(function(){
					$(".caseImg").animate({'left':300*-2 - 40},500,function(){
						$(".caseImg").css('left','-340px');
						$(".caseImg li:first").insertAfter(".caseImg li:last")
					})
				});
				$(".next").stop().click(function(){
					$(".caseImg").animate({'left':-40},500,function(){
						$(".caseImg").css('left','-340px');
						$(".caseImg li:last").insertBefore(".caseImg li:first")
					})
				});
				daovoice('init', {
					app_id: "8cb16f51"
				});
				daovoice('update');
        	},
        	onload (){
				var i=0;
				var oTag=null;
				
				var oDiv = this.oDiv;
				var aA = this.aA;
				var mcList = this.mcList;
				var active = this.active;
				var mouseX = this.mouseX;
				var mouseY = this.mouseY;
				
				oDiv=document.getElementById('div1');
				this.$set('oDiv',oDiv)
				aA=oDiv.getElementsByTagName('a');
				this.$set('aA',aA)
				for(i=0;i<aA.length;i++){
					oTag={};
			
					oTag.offsetWidth=aA[i].offsetWidth;
					oTag.offsetHeight=aA[i].offsetHeight;
			
					mcList.push(oTag);
				}
			
				this.sineCosine( 0,0,0 );
			
				this.positionAll();
			
				oDiv.onmouseover=function (){
					active=true;
				};
			
				oDiv.onmouseout=function (){
					active=false;
				};
			
				oDiv.onmousemove=function (ev){
					var oEvent=window.event || ev;
			
					mouseX=oEvent.clientX-(oDiv.offsetLeft+oDiv.offsetWidth/2);
					mouseY=oEvent.clientY-(oDiv.offsetTop+oDiv.offsetHeight/2);
			
					mouseX/=5;
					mouseY/=5;
				};
				this.$set('mouseX',mouseX)
				this.$set('mouseY',mouseY)
				this.$set('mcList',mcList)
				setInterval(this.update(), 30);
			},
			update(){
				var a;
				var b;
				
				var active = this.active;
				var mouseY = this.mouseY;
				var size = this.size;
				var radius = this.radius;
				var tspeed = this.tspeed;
				var lasta = this.lasta;
				var lastb = this.lastb;
				var mcList = this.mcList;
				var howElliptical = this.howElliptical;
				var sa = this.sa;
				var ca = this.ca;
				var sb = this.sb;
				var cb = this.cb;
				var sc = this.sc;
				var cc = this.cc;
				var d = this.d;
				
				
				if(active){
					a = (-Math.min( Math.max( -mouseY, -size ), size ) / radius ) * tspeed;
					b = (Math.min( Math.max( -mouseX, -size ), size ) / radius ) * tspeed;
				}
				else{
					a = lasta * 0.98;
					b = lastb * 0.98;
				}
			
				lasta=a;
				lastb=b;
				this.$set('lasta',lasta)
				this.$set('lastb',lastb)
				console.log(a)
				if(Math.abs(a)<=0.01 && Math.abs(b)<=0.01){
					return;
				}
				
				var c=0;
				this.sineCosine(a,b,c);
				console.log(mcList)
				for(var j=0;j<mcList.length;j++){
					var rx1=mcList[j].cx;
					var ry1=mcList[j].cy*ca+mcList[j].cz*(-sa);
					var rz1=mcList[j].cy*sa+mcList[j].cz*ca;
			
					var rx2=rx1*cb+rz1*sb;
					var ry2=ry1;
					var rz2=rx1*(-sb)+rz1*cb;
			
					var rx3=rx2*cc+ry2*(-sc);
					var ry3=rx2*sc+ry2*cc;
					var rz3=rz2;
			
					mcList[j].cx=rx3;
					mcList[j].cy=ry3;
					mcList[j].cz=rz3;
			
					var per=d/(d+rz3);
			
					mcList[j].x=(howElliptical*rx3*per)-(howElliptical*2);
					mcList[j].y=ry3*per;
					mcList[j].scale=per;
					mcList[j].alpha=per;
			
					mcList[j].alpha=(mcList[j].alpha-0.6)*(10/6);
				}
			
				this.doPosition();
				this.depthSort();
			},
			depthSort(){
				var i=0;
				var aTmp=[];
				
				var aA = this.aA;
				
				for(i=0;i<aA.length;i++){
					aTmp.push(aA[i]);
				}
			
				aTmp.sort(function(vItem1, vItem2){
					if(vItem1.cz>vItem2.cz){
						return -1;
					}
					else if(vItem1.cz<vItem2.cz){
						return 1;
					}
					else{
						return 0;
					}
				});
			
				for(i=0;i<aTmp.length;i++){
					aTmp[i].style.zIndex=i;
				}
			},
			positionAll(){
				var aA =this.aA;
				var oDiv =this.oDiv;
				var mcList =this.mcList;
				var distr =this.distr;
				var radius =this.radius;
				
				var phi=0;
				var theta=0;
				var max=mcList.length;
				var aTmp=[];
				var oFragment=document.createDocumentFragment();
				
				var i=0;
				//�������
				for(i=0;i<aA.length;i++){
					aTmp.push(aA[i]);
				}
			
				aTmp.sort(function(){
					return Math.random()<0.5?1:-1;
				});
			
				for(i=0;i<aTmp.length;i++){
					oFragment.appendChild(aTmp[i]);
				}
			
				oDiv.appendChild(oFragment);
			
				for( var i=1; i<max+1; i++){
					if( distr ){
						phi = Math.acos(-1+(2*i-1)/max);
						theta = Math.sqrt(max*Math.PI)*phi;
					}
					else{
						phi = Math.random()*(Math.PI);
						theta = Math.random()*(2*Math.PI);
					}
					//���任
					mcList[i-1].cx = radius * Math.cos(theta)*Math.sin(phi);
					mcList[i-1].cy = radius * Math.sin(theta)*Math.sin(phi);
					mcList[i-1].cz = radius * Math.cos(phi);
			
					aA[i-1].style.left=mcList[i-1].cx+oDiv.offsetWidth/1-mcList[i-1].offsetWidth/2+'px';
					aA[i-1].style.top=mcList[i-1].cy+oDiv.offsetHeight/1-mcList[i-1].offsetHeight/2+'px';
				}
			},
			
			doPosition(){
				var oDiv =this.oDiv;
				var aA =this.aA;
				var mcList =this.mcList;
				
				var l=oDiv.offsetWidth/2;
				var t=oDiv.offsetHeight/2;
				for(var i=0;i<mcList.length;i++){
					aA[i].style.left=mcList[i].cx+l-mcList[i].offsetWidth/2+'px';
					aA[i].style.top=mcList[i].cy+t-mcList[i].offsetHeight/2+'px';
			
					aA[i].style.fontSize=Math.ceil(12*mcList[i].scale/2)+8+'px';
			
					aA[i].style.filter="alpha(opacity="+100*mcList[i].alpha+")";
					aA[i].style.opacity=mcList[i].alpha;
				}
			},
			
			sineCosine( a, b, c){
				var dtr = Math.PI/180;
				this.$set('sa',Math.sin(a * dtr))
				this.$set('ca',Math.sin(a * dtr))
				this.$set('sb',Math.sin(b * dtr))
				this.$set('cb',Math.sin(b * dtr))
				this.$set('sc',Math.sin(c * dtr))
				this.$set('cc',Math.sin(c * dtr))
			},

        },
        components: {
        }
    }
</script>
