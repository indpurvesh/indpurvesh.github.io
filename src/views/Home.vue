<template>
<div>		
	<a-layout id="components-layout-demo-top-side-2">		
		<avored-header></avored-header>
	</a-layout>
</div>
</template>

<script>
import Header from '@/components/Header.vue'

export default {
  name: 'home',
  components: {
    'avored-header': Header
  }
}
</script>

<style>
body {
		margin: 0;
		padding: 0;
	}
	:root {
		--web-view-ids: Theme;
	}
	#Theme * {
		margin: 0;
		padding: 0;
	}
	#Theme {
		position: absolute;
		box-sizing: border-box;
		background: #E5E5E5;
		width: 1440px;
		height: 3801px;
		background-color: rgba(255,255,255,1);
		overflow: hidden;
		margin: 0;
		padding: 0;
		--web-view-name: Theme;
		--web-view-id: Theme;
		--web-enable-deep-linking: true;
	}
	#layer_83 {
		filter: drop-shadow(0px 3px 31px rgba(0, 0, 0, 0.161));
		fill: rgba(255,255,255,1);
	}
	.layer_83 {
		position: absolute;
		overflow: visible;
		width: 473px;
		height: 310px;
		left: 516px;
		top: 1380.325px;
	}
	
	#layer_81 {
		position: absolute;
		left: 963px;
		top: 40px;
		overflow: visible;
		width: 32px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 12px;
		color: rgba(0,0,0,1);
	}
	#layer_80 {
		position: absolute;
		left: 1019px;
		top: 40px;
		overflow: visible;
		width: 69px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 12px;
		color: rgba(0,0,0,1);
	}
	#layer_79 {
		position: absolute;
		left: 1112px;
		top: 40px;
		overflow: visible;
		width: 79px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 12px;
		color: rgba(0,0,0,1);
	}
	#layer_78 {
		position: absolute;
		left: 1215px;
		top: 40px;
		overflow: visible;
		width: 62px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 12px;
		color: rgba(0,0,0,1);
	}
	#layer_77 {
		position: absolute;
		left: 155px;
		top: 328px;
		overflow: visible;
		width: 542px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: normal;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_76 {
		position: absolute;
		left: 152px;
		top: 205px;
		overflow: hidden;
		width: 545px;
		height: 108px;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 40px;
		color: rgba(0,0,0,1);
	}
	#layer_75 {
		position: absolute;
		left: 152px;
		top: 782.968px;
		overflow: visible;
		width: 670px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 50px;
		color: rgba(0,0,0,1);
	}
	#layer_74 {
		filter: drop-shadow(0px 3px 31px rgba(0, 0, 0, 0.161));
		fill: rgba(255,255,255,1);
	}
	.layer_74 {
		position: absolute;
		overflow: visible;
		width: 414px;
		height: 152px;
		left: 156px;
		top: 492px;
	}
	#layer_73 {
		fill: url(#LinearGradientFill1);
	}
	.layer_73 {
		position: absolute;
		overflow: visible;
		width: 147px;
		height: 59px;
		left: 477px;
		top: 492px;
	}
	#layer_72 {
		opacity: 0.2;
		position: absolute;
		left: 170px;
		top: 512px;
		overflow: visible;
		width: 62px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_71 {
		position: absolute;
		left: 499px;
		top: 512px;
		overflow: visible;
		width: 80px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 15px;
		color: rgba(255,255,255,1);
	}
	#layer_70 {
		position: absolute;
		left: 156px;
		top: 929.427px;
		overflow: hidden;
		width: 637px;
		height: 97px;
		line-height: 30px;
		margin-top: -6px;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: normal;
		font-size: 18px;
		color: rgba(0,0,0,1);
	}
	#layer_69 {
		position: absolute;
		left: 156px;
		top: 1128.336px;
		overflow: visible;
		width: 174px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_68 {
		opacity: 0.8;
		position: absolute;
		left: 156px;
		top: 1165.053px;
		overflow: hidden;
		width: 261px;
		height: 155px;
		line-height: 20px;
		margin-top: -2.5px;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: normal;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_67 {
		position: absolute;
		left: 156px;
		top: 1419.26px;
		overflow: visible;
		width: 172px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_66 {
		opacity: 0.8;
		position: absolute;
		left: 156px;
		top: 1455.845px;
		overflow: hidden;
		width: 261px;
		height: 111px;
		line-height: 20px;
		margin-top: -2.5px;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: normal;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_65 {
		position: absolute;
		left: 590px;
		top: 1128.336px;
		overflow: visible;
		width: 156px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_64 {
		opacity: 0.8;
		position: absolute;
		left: 590px;
		top: 1165.053px;
		overflow: hidden;
		width: 261px;
		height: 155px;
		line-height: 20px;
		margin-top: -2.5px;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: normal;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_63 {
		position: absolute;
		left: 590px;
		top: 1419.26px;
		overflow: visible;
		width: 201px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_62 {
		opacity: 0.8;
		position: absolute;
		left: 590px;
		top: 1455.845px;
		overflow: hidden;
		width: 261px;
		height: 111px;
		line-height: 20px;
		margin-top: -2.5px;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: normal;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_61 {
		position: absolute;
		left: 1023px;
		top: 1128.336px;
		overflow: visible;
		width: 86px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_60 {
		opacity: 0.8;
		position: absolute;
		left: 1023px;
		top: 1165.053px;
		overflow: hidden;
		width: 261px;
		height: 155px;
		line-height: 20px;
		margin-top: -2.5px;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: normal;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_59 {
		position: absolute;
		left: 1023px;
		top: 1419.26px;
		overflow: visible;
		width: 158px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_58 {
		opacity: 0.8;
		position: absolute;
		left: 1023px;
		top: 1455.845px;
		overflow: hidden;
		width: 261px;
		height: 111px;
		line-height: 20px;
		margin-top: -2.5px;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: normal;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_57 {
		position: absolute;
		left: 160px;
		top: 1702.207px;
		overflow: visible;
		width: 306px;
		white-space: nowrap;
		line-height: 500px;
		margin-top: -242.5px;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: normal;
		font-size: 15px;
		color: rgba(0,0,0,1);
		letter-spacing: 5px;
	}
	#layer_56 {
		position: absolute;
		left: 156px;
		top: 1748.945px;
		overflow: visible;
		width: 517px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 50px;
		color: rgba(0,0,0,1);
	}
	#layer_55 {
		position: absolute;
		left: 160px;
		top: 1845.803px;
		overflow: hidden;
		width: 637px;
		height: 97px;
		line-height: 30px;
		margin-top: -6px;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: normal;
		font-size: 18px;
		color: rgba(0,0,0,1);
	}
	#layer_54 {
		filter: drop-shadow(0px 3px 39px rgba(0, 0, 0, 0.161));
		fill: rgba(255,255,255,1);
	}
	.layer_54 {
		position: absolute;
		overflow: visible;
		width: 652.939px;
		height: 182.845px;
		left: 166px;
		top: 1982.48px;
	}
	#layer_53 {
		filter: drop-shadow(0px 3px 39px rgba(0, 0, 0, 0.161));
		fill: rgba(255,255,255,1);
	}
	.layer_53 {
		position: absolute;
		overflow: visible;
		width: 652.939px;
		height: 182.845px;
		left: 166px;
		top: 2078.791px;
	}
	#layer_52 {
		filter: drop-shadow(0px 3px 39px rgba(0, 0, 0, 0.161));
		fill: rgba(255,255,255,1);
	}
	.layer_52 {
		position: absolute;
		overflow: visible;
		width: 652.939px;
		height: 182.845px;
		left: 166px;
		top: 2175.102px;
	}
	#layer_51 {
		fill: url(#LinearGradientFill2);
	}
	.layer_51 {
		position: absolute;
		overflow: visible;
		width: 535.939px;
		height: 65.845px;
		left: 726px;
		top: 1982.48px;
	}
	#layer_50 {
		filter: drop-shadow(0px 3px 39px rgba(0, 0, 0, 0.161));
		fill: rgba(255,255,255,1);
	}
	.layer_50 {
		position: absolute;
		overflow: visible;
		width: 652.939px;
		height: 182.845px;
		left: 726px;
		top: 2078.791px;
	}
	#layer_49 {
		filter: drop-shadow(0px 3px 39px rgba(0, 0, 0, 0.161));
		fill: rgba(255,255,255,1);
	}
	.layer_49 {
		position: absolute;
		overflow: visible;
		width: 652.939px;
		height: 182.845px;
		left: 726px;
		top: 2175.102px;
	}
	#layer_48 {
		fill: rgba(0,0,0,1);
	}
	.layer_48 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 2011.85px;
		left: 188px;
		width: 15.8px;
		height: 9.756px;
	}
	#layer_47 {
		fill: rgba(0,0,0,1);
	}
	.layer_47 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 2108.156px;
		left: 188px;
		width: 15.8px;
		height: 9.756px;
	}
	#layer_46 {
		fill: rgba(0,0,0,1);
	}
	.layer_46 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 2204.461px;
		left: 188px;
		width: 15.8px;
		height: 9.756px;
	}
	#layer_45 {
		fill: rgba(255,255,255,1);
	}
	.layer_45 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 2011.85px;
		left: 748px;
		width: 15.8px;
		height: 9.756px;
	}
	#layer_44 {
		fill: rgba(0,0,0,1);
	}
	.layer_44 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 2108.156px;
		left: 748px;
		width: 15.8px;
		height: 9.756px;
	}
	#layer_43 {
		fill: rgba(0,0,0,1);
	}
	.layer_43 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 2204.461px;
		left: 748px;
		width: 15.8px;
		height: 9.756px;
	}
	#layer_42 {
		position: absolute;
		left: 238px;
		top: 2005.847px;
		overflow: visible;
		width: 211px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_41 {
		position: absolute;
		left: 238px;
		top: 2102.147px;
		overflow: visible;
		width: 211px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_40 {
		position: absolute;
		left: 238px;
		top: 2198.448px;
		overflow: visible;
		width: 211px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_39 {
		position: absolute;
		left: 798px;
		top: 2005.847px;
		overflow: visible;
		width: 211px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 15px;
		color: rgba(255,255,255,1);
	}
	#layer_38 {
		position: absolute;
		left: 798px;
		top: 2102.147px;
		overflow: visible;
		width: 211px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_37 {
		position: absolute;
		left: 798px;
		top: 2198.448px;
		overflow: visible;
		width: 211px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_36 {
		opacity: 0.2;
		fill: rgba(212,223,236,1);
	}
	.layer_36 {
		position: absolute;
		overflow: visible;
		width: 91px;
		height: 35px;
		left: 591px;
		top: 1997.8px;
	}
	#layer_35 {
		opacity: 0.2;
		fill: rgba(212,223,236,1);
	}
	.layer_35 {
		position: absolute;
		overflow: visible;
		width: 91px;
		height: 35px;
		left: 591px;
		top: 2094.091px;
	}
	#layer_34 {
		opacity: 0.2;
		fill: rgba(212,223,236,1);
	}
	.layer_34 {
		position: absolute;
		overflow: visible;
		width: 91px;
		height: 35px;
		left: 591px;
		top: 2190.381px;
	}
	#layer_33 {
		filter: drop-shadow(0px 3px 31px rgba(0, 0, 0, 0.161));
		fill: rgba(255,255,255,1);
	}
	.layer_33 {
		position: absolute;
		overflow: visible;
		width: 184px;
		height: 128px;
		left: 1151px;
		top: 1997.8px;
	}
	#layer_32 {
		opacity: 0.2;
		fill: rgba(212,223,236,1);
	}
	.layer_32 {
		position: absolute;
		overflow: visible;
		width: 91px;
		height: 35px;
		left: 1151px;
		top: 2094.091px;
	}
	#layer_31 {
		opacity: 0.2;
		fill: rgba(212,223,236,1);
	}
	.layer_31 {
		position: absolute;
		overflow: visible;
		width: 91px;
		height: 35px;
		left: 1151px;
		top: 2190.381px;
	}
	#layer_30 {
		opacity: 0.2;
		position: absolute;
		left: 609px;
		top: 2007.847px;
		overflow: visible;
		width: 57px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 13px;
		color: rgba(0,0,0,1);
	}
	#layer_29 {
		opacity: 0.2;
		position: absolute;
		left: 609px;
		top: 2104.149px;
		overflow: visible;
		width: 57px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 13px;
		color: rgba(0,0,0,1);
	}
	#layer_28 {
		opacity: 0.2;
		position: absolute;
		left: 609px;
		top: 2200.451px;
		overflow: visible;
		width: 57px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 13px;
		color: rgba(0,0,0,1);
	}
	#layer_27 {
		position: absolute;
		left: 1169px;
		top: 2007.847px;
		overflow: visible;
		width: 57px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 13px;
		color: rgba(0,0,0,1);
	}
	#layer_26 {
		position: absolute;
		left: 1169px;
		top: 2104.149px;
		overflow: visible;
		width: 57px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 13px;
		color: rgba(0,0,0,1);
	}
	#layer_25 {
		position: absolute;
		left: 1169px;
		top: 2200.451px;
		overflow: visible;
		width: 57px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 13px;
		color: rgba(0,0,0,1);
	}
	#layer_24 {
		position: absolute;
		left: 190px;
		top: 2664.005px;
		overflow: visible;
		width: 103px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 18px;
		color: rgba(0,0,0,1);
	}
	#layer_23 {
		position: absolute;
		left: 578px;
		top: 2664.005px;
		overflow: visible;
		width: 75px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 18px;
		color: rgba(0,0,0,1);
	}
	#layer_22 {
		position: absolute;
		left: 872px;
		top: 2664.005px;
		overflow: visible;
		width: 70px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 18px;
		color: rgba(0,0,0,1);
	}
	#layer_21 {
		position: absolute;
		left: 190px;
		top: 2735.005px;
		overflow: visible;
		width: 184px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: normal;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_20 {
		position: absolute;
		left: 574px;
		top: 2735.005px;
		overflow: visible;
		width: 176px;
		white-space: nowrap;
		line-height: 45px;
		margin-top: -15px;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: normal;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_19 {
		position: absolute;
		left: 868px;
		top: 2735.005px;
		overflow: visible;
		width: 176px;
		white-space: nowrap;
		line-height: 45px;
		margin-top: -15px;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: normal;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_18 {
		position: absolute;
		left: 218px;
		top: 2812.005px;
		overflow: visible;
		width: 102px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_17 {
		position: absolute;
		left: 218px;
		top: 2866.005px;
		overflow: visible;
		width: 102px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_16 {
		fill: url(#LinearGradientFill3);
		stroke: rgb(112, 112, 112);
		stroke-width: 1px;
		stroke-linejoin: miter;
		stroke-linecap: butt;
		stroke-miterlimit: 4;
		shape-rendering: auto;
	}
	.layer_16 {
		position: absolute;
		overflow: visible;
		width: 1440px;
		height: 213px;
		left: 0px;
		top: 2375.005px;
	}
	#layer_15 {
		position: absolute;
		left: 190px;
		top: 2468.005px;
		overflow: visible;
		width: 320px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 22px;
		color: rgba(255,255,255,1);
	}
	#layer_14 {
		fill: rgba(255,255,255,1);
	}
	.layer_14 {
		position: absolute;
		overflow: visible;
		width: 540px;
		height: 58px;
		left: 564px;
		top: 2453.005px;
	}
	#layer_13 {
		fill: url(#LinearGradientFill4);
	}
	.layer_13 {
		position: absolute;
		overflow: visible;
		width: 154px;
		height: 58px;
		left: 1104px;
		top: 2453.005px;
	}
	#layer_12 {
		opacity: 0.2;
		position: absolute;
		left: 592px;
		top: 2473.005px;
		overflow: visible;
		width: 156px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 15px;
		color: rgba(0,0,0,1);
	}
	#layer_11 {
		fill: rgba(231,239,253,1);
	}
	.layer_11 {
		position: absolute;
		overflow: visible;
		width: 7.238px;
		height: 7.238px;
		left: 896.716px;
		top: 120.772px;
	}
	#layer_10 {
		fill: rgba(231,239,253,1);
	}
	.layer_10 {
		position: absolute;
		overflow: visible;
		width: 7.238px;
		height: 7.238px;
		left: 780.819px;
		top: 113.525px;
	}
	#layer_9 {
		fill: rgba(231,239,253,1);
	}
	.layer_9 {
		position: absolute;
		overflow: visible;
		width: 3.107px;
		height: 3.107px;
		left: 939.659px;
		top: 122.837px;
	}
	#layer_8 {
		fill: rgba(231,239,253,1);
	}
	.layer_8 {
		position: absolute;
		overflow: visible;
		width: 3.107px;
		height: 3.107px;
		left: 823.241px;
		top: 119.218px;
	}
	#layer_7 {
		fill: rgba(231,239,253,1);
	}
	.layer_7 {
		position: absolute;
		overflow: visible;
		width: 3.107px;
		height: 3.107px;
		left: 821.697px;
		top: 227.733px;
	}
	#layer_6 {
		fill: rgba(231,239,253,1);
	}
	.layer_6 {
		position: absolute;
		overflow: visible;
		width: 3.107px;
		height: 3.107px;
		left: 1012.092px;
		top: 147.155px;
	}
	#layer_5 {
		position: absolute;
		left: 1124px;
		top: 2468.005px;
		overflow: visible;
		width: 115px;
		white-space: nowrap;
		text-align: left;
		font-family: Montserrat;
		font-style: normal;
		font-weight: bold;
		font-size: 22px;
		color: rgba(255,255,255,1);
	}
	#layer_4 {
		fill: rgba(0,0,0,1);
	}
	.layer_4 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 2817.005px;
		left: 190px;
		width: 18px;
		height: 18px;
	}
	#layer_3 {
		fill: rgba(0,0,0,1);
	}
	.layer_3 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 2869.005px;
		left: 191px;
		width: 20px;
		height: 16px;
	}
	#layer_2 {
		position: absolute;
		width: 718.506px;
		height: 454.511px;
		left: 716px;
		top: 140px;
		overflow: visible;
	}
	#Path_199 {
		opacity: 0.1;
		fill: rgba(193,46,50,1);
	}
	.Path_199 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 0.772px;
		left: 106.668px;
		width: 611.838px;
		height: 386.561px;
	}
	#flowers {
		position: absolute;
		width: 288.097px;
		height: 324.879px;
		left: 0px;
		top: 0px;
		overflow: visible;
	}
	#Path_200 {
		fill: transparent;
		stroke: rgb(83, 84, 97);
		stroke-width: 2px;
		stroke-linejoin: miter;
		stroke-linecap: butt;
		stroke-miterlimit: 10;
		shape-rendering: auto;
	}
	.Path_200 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 128.019px;
		left: 49.64px;
		width: 210.146px;
		height: 197.755px;
	}
	#Path_201 {
		fill: rgba(193,46,50,1);
	}
	.Path_201 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 78.739px;
		left: 0px;
		width: 50.73px;
		height: 49.82px;
	}
	#Path_202 {
		fill: rgba(193,46,50,1);
	}
	.Path_202 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 139.543px;
		left: 10.801px;
		width: 62.059px;
		height: 39.708px;
	}
	#Path_203 {
		fill: rgba(193,46,50,1);
	}
	.Path_203 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 212.001px;
		left: 75.522px;
		width: 61.088px;
		height: 39.861px;
	}
	#Path_204 {
		fill: rgba(193,46,50,1);
	}
	.Path_204 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 252.266px;
		left: 148.931px;
		width: 62.279px;
		height: 39.752px;
	}
	#Path_205 {
		fill: rgba(193,46,50,1);
	}
	.Path_205 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 118.933px;
		left: 63.645px;
		width: 39.86px;
		height: 63.286px;
	}
	#Path_206 {
		fill: rgba(193,46,50,1);
	}
	.Path_206 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 163.402px;
		left: 145.431px;
		width: 39.355px;
		height: 60.157px;
	}
	#Path_207 {
		fill: rgba(193,46,50,1);
	}
	.Path_207 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 224.522px;
		left: 216.458px;
		width: 39.785px;
		height: 62.467px;
	}
	#Path_208 {
		opacity: 0.25;
		fill: rgba(0,0,0,1);
	}
	.Path_208 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 78.739px;
		left: 0px;
		width: 50.73px;
		height: 49.82px;
	}
	#Path_209 {
		opacity: 0.25;
		fill: rgba(0,0,0,1);
	}
	.Path_209 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 139.543px;
		left: 10.801px;
		width: 62.059px;
		height: 39.708px;
	}
	#Path_210 {
		opacity: 0.25;
		fill: rgba(0,0,0,1);
	}
	.Path_210 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 212.001px;
		left: 75.522px;
		width: 61.088px;
		height: 39.861px;
	}
	#Path_211 {
		opacity: 0.25;
		fill: rgba(0,0,0,1);
	}
	.Path_211 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 252.266px;
		left: 148.931px;
		width: 62.279px;
		height: 39.752px;
	}
	#Path_212 {
		opacity: 0.25;
		fill: rgba(0,0,0,1);
	}
	.Path_212 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 118.933px;
		left: 63.645px;
		width: 39.86px;
		height: 63.286px;
	}
	#Path_213 {
		opacity: 0.25;
		fill: rgba(0,0,0,1);
	}
	.Path_213 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 163.402px;
		left: 145.431px;
		width: 39.355px;
		height: 60.157px;
	}
	#Path_214 {
		opacity: 0.25;
		fill: rgba(0,0,0,1);
	}
	.Path_214 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 224.522px;
		left: 216.458px;
		width: 39.785px;
		height: 62.467px;
	}
	#Path_215 {
		fill: transparent;
		stroke: rgb(83, 84, 97);
		stroke-width: 2px;
		stroke-linejoin: miter;
		stroke-linecap: butt;
		stroke-miterlimit: 10;
		shape-rendering: auto;
	}
	.Path_215 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 58.829px;
		left: 144.65px;
		width: 112.696px;
		height: 264.528px;
	}
	#Path_216 {
		fill: rgba(193,46,50,1);
	}
	.Path_216 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 0px;
		left: 109.421px;
		width: 39.804px;
		height: 59.759px;
	}
	#Path_217 {
		fill: rgba(193,46,50,1);
	}
	.Path_217 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 60.008px;
		left: 94.664px;
		width: 55.016px;
		height: 44.641px;
	}
	#Path_218 {
		fill: rgba(193,46,50,1);
	}
	.Path_218 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 152.507px;
		left: 124.72px;
		width: 63.14px;
		height: 39.859px;
	}
	#Path_219 {
		fill: rgba(193,46,50,1);
	}
	.Path_219 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 218.946px;
		left: 175.335px;
		width: 61.475px;
		height: 39.658px;
	}
	#Path_220 {
		fill: rgba(193,46,50,1);
	}
	.Path_220 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 62.984px;
		left: 151.091px;
		width: 39.934px;
		height: 59.175px;
	}
	#Path_221 {
		fill: rgba(193,46,50,1);
	}
	.Path_221 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 135.602px;
		left: 199.82px;
		width: 48.242px;
		height: 52.167px;
	}
	#Path_222 {
		fill: rgba(193,46,50,1);
	}
	.Path_222 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 220.982px;
		left: 245.668px;
		width: 42.43px;
		height: 56.517px;
	}
	#Ellipse_10 {
		opacity: 0.1;
		fill: rgba(193,46,50,1);
	}
	.Ellipse_10 {
		position: absolute;
		overflow: visible;
		width: 223.06px;
		height: 29.04px;
		left: 164.552px;
		top: 412.68px;
	}
	#floor_flowers {
		position: absolute;
		width: 504.276px;
		height: 85.6px;
		left: 105.258px;
		top: 361.5px;
		overflow: visible;
	}
	#Ellipse_11 {
		opacity: 0.1;
		fill: rgba(193,46,50,1);
	}
	.Ellipse_11 {
		position: absolute;
		overflow: visible;
		width: 67.76px;
		height: 11.6px;
		left: 2.843px;
		top: 58.78px;
	}
	#Path_223 {
		fill: rgba(193,46,50,1);
	}
	.Path_223 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 0px;
		left: 28.95px;
		width: 27.474px;
		height: 44.77px;
	}
	#Path_224 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_224 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 0px;
		left: 29.283px;
		width: 27.162px;
		height: 44.8px;
	}
	#Path_225 {
		fill: rgba(255,208,55,1);
	}
	.Path_225 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 7.522px;
		left: 53.023px;
		width: 1.27px;
		height: 6.218px;
	}
	#Path_226 {
		fill: rgba(255,208,55,1);
	}
	.Path_226 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 10.441px;
		left: 53.461px;
		width: 5.691px;
		height: 3.44px;
	}
	#Path_227 {
		fill: rgba(193,46,50,1);
	}
	.Path_227 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 0px;
		left: 2.727px;
		width: 27.469px;
		height: 44.77px;
	}
	#Path_228 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_228 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 0px;
		left: 2.706px;
		width: 27.158px;
		height: 44.8px;
	}
	#Path_229 {
		fill: rgba(255,208,55,1);
	}
	.Path_229 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 7.522px;
		left: 4.853px;
		width: 1.27px;
		height: 6.218px;
	}
	#Path_230 {
		fill: rgba(255,208,55,1);
	}
	.Path_230 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 10.441px;
		left: 0px;
		width: 5.685px;
		height: 3.44px;
	}
	#Path_231 {
		fill: rgba(168,168,168,1);
	}
	.Path_231 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 35.557px;
		left: 6.603px;
		width: 57.158px;
		height: 29.018px;
	}
	#Path_232 {
		opacity: 0.2;
		fill: rgba(0,0,0,1);
	}
	.Path_232 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 43.84px;
		left: 6.603px;
		width: 57.144px;
		height: 20.715px;
	}
	#Path_233 {
		fill: rgba(193,46,50,1);
	}
	.Path_233 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 43.215px;
		left: 465.773px;
		width: 38.503px;
		height: 34.745px;
	}
	#Ellipse_12 {
		opacity: 0.1;
		fill: rgba(193,46,50,1);
	}
	.Ellipse_12 {
		position: absolute;
		overflow: visible;
		width: 59.84px;
		height: 10.12px;
		left: 444.433px;
		top: 75.48px;
	}
	#Path_234 {
		fill: rgba(193,46,50,1);
	}
	.Path_234 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 44.819px;
		left: 408.168px;
		width: 21.717px;
		height: 19.591px;
	}
	#Ellipse_13 {
		opacity: 0.1;
		fill: rgba(193,46,50,1);
	}
	.Ellipse_13 {
		position: absolute;
		overflow: visible;
		width: 33.74px;
		height: 5.7px;
		left: 396.113px;
		top: 63.02px;
	}
	#Path_235 {
		fill: rgba(193,46,50,1);
	}
	.Path_235 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 9.402px;
		left: 449.115px;
		width: 26.21px;
		height: 23.648px;
	}
	#Ellipse_14 {
		opacity: 0.1;
		fill: rgba(193,46,50,1);
	}
	.Ellipse_14 {
		position: absolute;
		overflow: visible;
		width: 40.74px;
		height: 6.88px;
		left: 434.593px;
		top: 31.37px;
	}
	#browser {
		position: absolute;
		width: 595.789px;
		height: 316.32px;
		left: 94.619px;
		top: 65.506px;
		overflow: visible;
	}
	#Path_236 {
		fill: url(#LinearGradientFill5);
	}
	.Path_236 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 0px;
		left: 0px;
		width: 595.789px;
		height: 316.24px;
	}
	#Path_237 {
		fill: rgba(255,255,255,1);
	}
	.Path_237 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 14px;
		left: 2.08px;
		width: 591.869px;
		height: 302.32px;
	}
	#Rectangle_91 {
		fill: rgba(90,87,115,1);
	}
	.Rectangle_91 {
		position: absolute;
		overflow: visible;
		width: 591.859px;
		height: 25.14px;
		left: 2.09px;
		top: 1.39px;
	}
	#buttons {
		position: absolute;
		width: 48px;
		height: 13px;
		left: 107.763px;
		top: 79.278px;
		overflow: visible;
	}
	#Ellipse_15 {
		fill: rgba(255,255,255,1);
	}
	.Ellipse_15 {
		position: absolute;
		overflow: visible;
		width: 13px;
		height: 13px;
		left: 0px;
		top: 0px;
	}
	#Ellipse_16 {
		fill: rgba(255,255,255,1);
	}
	.Ellipse_16 {
		position: absolute;
		overflow: visible;
		width: 13px;
		height: 13px;
		left: 17.5px;
		top: 0px;
	}
	#Ellipse_17 {
		fill: rgba(255,255,255,1);
	}
	.Ellipse_17 {
		position: absolute;
		overflow: visible;
		width: 13px;
		height: 13px;
		left: 35px;
		top: 0px;
	}
	#boxes {
		position: absolute;
		width: 322.88px;
		height: 230.853px;
		left: 98.72px;
		top: 122.7px;
		overflow: visible;
	}
	#Rectangle_92 {
		fill: rgba(193,46,50,1);
	}
	.Rectangle_92 {
		position: absolute;
		overflow: visible;
		width: 156.5px;
		height: 98.34px;
		left: 83.19px;
		top: 0px;
	}
	#Rectangle_93 {
		opacity: 0.2;
		fill: rgba(90,87,115,1);
	}
	.Rectangle_93 {
		position: absolute;
		overflow: visible;
		width: 156.5px;
		height: 98.34px;
		left: 0px;
		top: 0px;
	}
	#Rectangle_94 {
		opacity: 0.2;
		fill: rgba(90,87,115,1);
	}
	.Rectangle_94 {
		position: absolute;
		overflow: visible;
		width: 156.5px;
		height: 98.34px;
		left: 166.38px;
		top: 0px;
	}
	#Rectangle_95 {
		opacity: 0.2;
		fill: rgba(90,87,115,1);
	}
	.Rectangle_95 {
		position: absolute;
		overflow: visible;
		width: 156.5px;
		height: 98.34px;
		left: 0px;
		top: 66.259px;
	}
	#Rectangle_96 {
		opacity: 0.2;
		fill: rgba(90,87,115,1);
	}
	.Rectangle_96 {
		position: absolute;
		overflow: visible;
		width: 156.5px;
		height: 98.34px;
		left: 83.19px;
		top: 66.259px;
	}
	#Rectangle_97 {
		opacity: 0.2;
		fill: rgba(90,87,115,1);
	}
	.Rectangle_97 {
		position: absolute;
		overflow: visible;
		width: 156.5px;
		height: 98.34px;
		left: 166.38px;
		top: 66.259px;
	}
	#Rectangle_98 {
		opacity: 0.2;
		fill: rgba(90,87,115,1);
	}
	.Rectangle_98 {
		position: absolute;
		overflow: visible;
		width: 156.5px;
		height: 98.34px;
		left: 0px;
		top: 132.512px;
	}
	#Rectangle_99 {
		opacity: 0.2;
		fill: rgba(90,87,115,1);
	}
	.Rectangle_99 {
		position: absolute;
		overflow: visible;
		width: 156.5px;
		height: 98.34px;
		left: 83.19px;
		top: 132.512px;
	}
	#Rectangle_100 {
		opacity: 0.2;
		fill: rgba(90,87,115,1);
	}
	.Rectangle_100 {
		position: absolute;
		overflow: visible;
		width: 156.5px;
		height: 98.34px;
		left: 166.38px;
		top: 132.512px;
	}
	#woman {
		position: absolute;
		width: 128.25px;
		height: 322.611px;
		left: 226.793px;
		top: 131.9px;
		overflow: visible;
	}
	#Path_238 {
		fill: url(#LinearGradientFill6);
	}
	.Path_238 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 0px;
		left: 0px;
		width: 128.25px;
		height: 322.611px;
	}
	#Path_239 {
		fill: rgba(239,183,185,1);
	}
	.Path_239 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 2.02px;
		left: 81.292px;
		width: 26.991px;
		height: 63.382px;
	}
	#Path_240 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_240 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 55.322px;
		left: 93.224px;
		width: 14.72px;
		height: 10.08px;
	}
	#Path_241 {
		fill: rgba(255,100,132,1);
	}
	.Path_241 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 51.595px;
		left: 87.061px;
		width: 34.836px;
		height: 86.706px;
	}
	#Path_242 {
		fill: rgba(239,183,185,1);
	}
	.Path_242 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 138.896px;
		left: 4.889px;
		width: 27.952px;
		height: 54.518px;
	}
	#Path_243 {
		fill: rgba(239,183,185,1);
	}
	.Path_243 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 225.214px;
		left: 19.453px;
		width: 27.313px;
		height: 49.128px;
	}
	#Path_244 {
		fill: rgba(239,183,185,1);
	}
	.Path_244 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 239.682px;
		left: 53.622px;
		width: 22.027px;
		height: 45.9px;
	}
	#Path_245 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_245 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 253.236px;
		left: 19.165px;
		width: 22.295px;
		height: 13.828px;
	}
	#Path_246 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_246 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 253.593px;
		left: 56.824px;
		width: 18.24px;
		height: 11.806px;
	}
	#Path_247 {
		fill: rgba(68,64,83,1);
	}
	.Path_247 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 31.885px;
		left: 17.783px;
		width: 93.599px;
		height: 260.24px;
	}
	#Ellipse_18 {
		fill: rgba(161,97,106,1);
	}
	.Ellipse_18 {
		position: absolute;
		overflow: visible;
		width: 57.46px;
		height: 57.46px;
		left: 34.208px;
		top: 32.852px;
	}
	#Path_248 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_248 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 121.205px;
		left: 32.64px;
		width: 63.281px;
		height: 37.534px;
	}
	#Path_249 {
		fill: rgba(255,100,132,1);
	}
	.Path_249 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 44.824px;
		left: 10.848px;
		width: 114.053px;
		height: 191.002px;
	}
	#Path_250 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_250 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 55.692px;
		left: 4.03px;
		width: 40.858px;
		height: 155.555px;
	}
	#Path_251 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_251 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 149.237px;
		left: 8.16px;
		width: 18.77px;
		height: 15.18px;
	}
	#Path_252 {
		fill: rgba(255,100,132,1);
	}
	.Path_252 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 55.674px;
		left: 3.41px;
		width: 40.843px;
		height: 155.575px;
	}
	#Path_253 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_253 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 86.088px;
		left: 71.956px;
		width: 24.58px;
		height: 55.38px;
	}
	#Path_254 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_254 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 94.352px;
		left: 33.5px;
		width: 15.689px;
		height: 17.445px;
	}
	#Path_255 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_255 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 103.647px;
		left: 33.975px;
		width: 10.328px;
		height: 18.115px;
	}
	#Path_256 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_256 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 55.89px;
		left: 100.917px;
		width: 5.397px;
		height: 14.706px;
	}
	#Path_257 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_257 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 63.228px;
		left: 99.131px;
		width: 10.275px;
		height: 1.858px;
	}
	#Path_258 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_258 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 160.609px;
		left: 57.533px;
		width: 36.28px;
		height: 18.44px;
	}
	#Path_259 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_259 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 177.524px;
		left: 26.041px;
		width: 32.79px;
		height: 4.481px;
	}
	#Path_260 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_260 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 181.638px;
		left: 29.261px;
		width: 16.39px;
		height: 1.762px;
	}
	#Path_261 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_261 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 183.874px;
		left: 30.228px;
		width: 15.14px;
		height: 2px;
	}
	#Path_262 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_262 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 210.894px;
		left: 28.988px;
		width: 24.52px;
		height: 3.011px;
	}
	#Path_263 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_263 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 215.575px;
		left: 29.467px;
		width: 19.058px;
		height: 1.947px;
	}
	#Path_264 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_264 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 216.97px;
		left: 29.184px;
		width: 22.328px;
		height: 3.257px;
	}
	#Path_265 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_265 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 250.55px;
		left: 19.57px;
		width: 22.48px;
		height: 23.801px;
	}
	#Path_266 {
		fill: rgba(68,64,83,1);
	}
	.Path_266 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 251.165px;
		left: 11.851px;
		width: 34.806px;
		height: 65.387px;
	}
	#Path_267 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_267 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 280.072px;
		left: 13.97px;
		width: 22.67px;
		height: 36.43px;
	}
	#Path_268 {
		fill: rgba(68,64,83,1);
	}
	.Path_268 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 280.062px;
		left: 23.552px;
		width: 8.795px;
		height: 42.54px;
	}
	#Path_269 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_269 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 257.25px;
		left: 53.823px;
		width: 20.777px;
		height: 28.332px;
	}
	#Path_270 {
		fill: rgba(68,64,83,1);
	}
	.Path_270 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 257.885px;
		left: 47.668px;
		width: 34.127px;
		height: 52.317px;
	}
	#Path_271 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_271 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 283.834px;
		left: 54.614px;
		width: 22.15px;
		height: 26.369px;
	}
	#Path_272 {
		fill: rgba(68,64,83,1);
	}
	.Path_272 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 280.072px;
		left: 56.006px;
		width: 5.72px;
		height: 36.43px;
	}
	#Path_273 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_273 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 15.726px;
		left: 11.217px;
		width: 98.229px;
		height: 216.396px;
	}
	#Path_274 {
		fill: rgba(146,89,120,1);
	}
	.Path_274 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 14.456px;
		left: 11.214px;
		width: 98.259px;
		height: 216.416px;
	}
	#Group_18 {
		opacity: 0.1;
		position: absolute;
		width: 98.297px;
		height: 201.32px;
		left: 11.209px;
		top: 29.472px;
		overflow: visible;
	}
	#Path_275 {
		fill: rgba(0,0,0,1);
	}
	.Path_275 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 0px;
		left: 23.652px;
		width: 0.06px;
		height: 1.16px;
	}
	#Path_276 {
		fill: rgba(0,0,0,1);
	}
	.Path_276 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 24.13px;
		left: 88.714px;
		width: 1.282px;
		height: 15.9px;
	}
	#Path_277 {
		fill: rgba(0,0,0,1);
	}
	.Path_277 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 48.19px;
		left: 7.799px;
		width: 4.413px;
		height: 23.2px;
	}
	#Path_278 {
		fill: rgba(0,0,0,1);
	}
	.Path_278 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 73.7px;
		left: 91.708px;
		width: 6.589px;
		height: 29.73px;
	}
	#Path_279 {
		fill: rgba(0,0,0,1);
	}
	.Path_279 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 91.55px;
		left: 0px;
		width: 24.099px;
		height: 42.64px;
	}
	#Path_280 {
		fill: rgba(0,0,0,1);
	}
	.Path_280 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 134.3px;
		left: 35.95px;
		width: 58.495px;
		height: 67.02px;
	}
	#Path_281 {
		fill: rgba(0,0,0,1);
	}
	.Path_281 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 161.245px;
		left: 18.333px;
		width: 26.042px;
		height: 30.565px;
	}
	#Path_282 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_282 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 113.399px;
		left: 18.87px;
		width: 9.274px;
		height: 2.773px;
	}
	#Path_283 {
		opacity: 0.1;
		fill: rgba(0,0,0,1);
	}
	.Path_283 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 116.091px;
		left: 19.833px;
		width: 9.286px;
		height: 2.773px;
	}
	#leaves {
		position: absolute;
		width: 110.489px;
		height: 66.353px;
		left: 433.755px;
		top: 8.619px;
		overflow: visible;
	}
	#Path_284 {
		opacity: 0.1;
		fill: rgba(193,46,50,1);
	}
	.Path_284 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 21.571px;
		left: 75.819px;
		width: 34.67px;
		height: 31.269px;
	}
	#Path_285 {
		opacity: 0.1;
		fill: rgba(193,46,50,1);
	}
	.Path_285 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 0px;
		left: 36.678px;
		width: 24.073px;
		height: 43.139px;
	}
	#Path_286 {
		opacity: 0.1;
		fill: rgba(193,46,50,1);
	}
	.Path_286 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 24.04px;
		left: 0px;
		width: 24.419px;
		height: 42.313px;
	}
	#Path_287 {
		fill: rgba(193,46,50,1);
	}
	.Path_287 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 126.821px;
		left: 466.869px;
		width: 143.132px;
		height: 140.91px;
	}
	#Path_288 {
		fill: rgba(255,255,255,1);
	}
	.Path_288 {
		transform: matrix(1,0,0,1,0,0);
		overflow: visible;
		position: absolute;
		top: 162.921px;
		left: 565.923px;
		width: 33px;
		height: 33px;
	}
	#layer_1 {
		fill: url(#layer_1_A0_Rectangle_30_pattern);
	}
	.layer_1 {
		position: absolute;
		overflow: visible;
		width: 44px;
		height: 49px;
		left: 134px;
		top: 31px;
	}
</style>

