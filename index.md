<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<title>滤镜</title>
		<style type="text/css">
			img{
				height: auto;
				width: 400px;
				display: block;
				margin: auto;
				/* 滤镜属性
				 *grayscale：设置灰度，1是百分之百，0是百分之0
				 */
				-webkit-filter:grayscale(0.5);
				transition: all 3s;
			}
			img:hover{
				-webkit-filter: none;
			}
			.img1{
				-webkit-filter:grayscale(1);
				/* transition: all 3s; */
			}
			.img2{
				/* 滤镜属性
				 *brightness：设置亮度，默认是1，正常亮度1是百分之百，0是百分之0
				 */
				-webkit-filter:brightness(1.5);
				/* transition: all 2s; */
			}
			.img3{
				/* 滤镜属性
				 *sepia：褐色属性，默认是1，正常褐色1是百分之百，0是百分之0
				 */
				-webkit-filter:sepia(0.9);
				/* transition: all 2s; */
			}
			.img4{
				/* 模糊度
				 *blur：模糊属性，单位像素
				 */
				-webkit-filter:blur(10px);
				/* transition: all 2s; */
			}
			.img5{
				/* 对比度
				 *contrast：对比度，正常是1
				 */
				-webkit-filter:contrast(0.5);
				/* transition: all 2s; */
			}
			.img6{
				/* 饱和度
				 *contrast：饱和，正常是1
				 */
				-webkit-filter:saturate(2);
				/* transition: all 2s; */
			}
			.img7{
				/* 胶片底色
				 *invert：胶片底色，正常是0
				 */
				-webkit-filter:invert(0.8);
				/* transition: all 2s; */
			}
			.img8{
				/* 色相旋转
				 *hue-rotate：
				 */
				-webkit-filter:hue-rotate(90deg);
				/* transition: all 2s; */
			}
			.img9{
				/* 素描*/
				-webkit-filter:blur(20px) blurbrightness(10) grayscale(1);
				transition: all 10s;
			}
			.img9:hover{
				-webkit-filter:blur(0) brightness(1) grayscale(1)
				
			}
		</style>
	</head>
	<body>
		
		<img class="img1" src="img/src=http___b-ssl.duitang.gif" ><br>
		<img class="img2" src="img/src=http___b-ssl.duitang.gif" ><br>
		<img class="img3" src="img/src=http___b-ssl.duitang.gif" ><br>
		<img class="img4" src="img/src=http___b-ssl.duitang.gif" ><br>
		<img class="img5" src="img/src=http___b-ssl.duitang.gif" ><br>
		<img class="img6" src="img/src=http___b-ssl.duitang.gif" ><br>
		<img class="img7" src="img/src=http___b-ssl.duitang.gif" ><br>
		<img class="img8" src="img/src=http___b-ssl.duitang.gif" ><br>
		<img class="img9" src="img/src=http___b-ssl.duitang.gif" ><br>
	</body>
</html>
