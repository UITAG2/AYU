<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Document</title>
	<style>
		.main-link01 { 
			width: 550px; height: 100px;
			font-size: 25px;
			background-color: darkgrey;
			color: white;
			display: inline-block;
			position: relative;
			border-radius: 5px;
			line-height: 100px;
			text-decoration-line: none;
			top: 80px;
			left: 300px;
		}
		img {
			position: absolute;
			left: 30px;
			top: 20px;
		}
		.main-link02 { 
			width: 550px; height: 100px;
			font-size: 25px;
			background-color: darkgrey;
			color: white;
			display: inline-block;
			position: relative;
			border-radius: 5px;
			line-height: 100px;
			text-decoration-line: none;
			top: 80px;
			left: 430px;
		}
		body {
			height: 100vh;
    		background: url(https://image.fnnews.com/resource/media/image/2022/01/19/202201191303150219_l.jpg) no-repeat center;
   			background-size: cover;
			/* 배경 이미지 선명하게 하기 */
			image-rendering: -webkit-optimize-contrast; /* chrome */
			image-rendering: crisp-edges;
			transform: translateZ(0);
			backface-visibility: hidden;

			background-repeat: no-repeat;
			background-size: cover;
			background-attachment: fixed;
		}
		.in-con01 {
			width: 450px; height: 100px;
			font-size: 15px;
			background-color: darkgrey;
			color: white;
			display: inline-block;
			position: relative;
			border-radius: 5px;
			line-height: 100px;
			text-decoration-line: none;
			top: 90px;
			left: 250px;
		}
		.in-con02 {
			width: 550px; height: 100px;
			font-size: 25px;
			background-color: darkgrey;
			color: white;
			display: inline-block;
			position: relative;
			border-radius: 5px;
			line-height: 100px;
			text-decoration-line: none;
			top: 90px;
			left: 300px;
		}
	</style>
</head>
<body>
	<!--전체적인 문제점
		1. 배경 이미지가 흐릿함
		2. main-linkBox의 글자들이 흐릿함 = body로 잡아놔서 그런듯
		포지션은 쌓는 것이다.

		<style>
			#event-test {
				background: red;
				height: 100vh;
				position: relative;
			}
			.overlay {
				position: fixed;
				top: 100px;
				left: 100px;
				width: 100%;
				height: 100%;
				background: rgba(0, 0, 255, 0.2);
			}
		</style>
		<body>
			<div id="event-test">
				<div class="overlay"></div>
			</div>
		</body>
	-->
	<div class="inner">
		<div class="main-linkBox">
			<a class="main-link01" href="https://www.anyang.ac.kr">
				<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQiOtYWgw9Yz0VZN91BQapj1QSy0GWeNrHJepYuBGIu38U1pj1A", width="60px", height="60px">
				&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
				<strong>안양대학교 홈페이지&nbsp;</strong>
				<span>바로가기</span>
				<!--화살표 이미지 코드 작성-->
			</a>
			<a class="main-link02" href="https://enter.anyang.ac.kr/enter/main.do">
				<img src="https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcT7rC-LXSafeJ-SSxpPH5I1Lx28tpeg5VJI9w9MpmFVshXTVaWO", width="60px", height="60px">
				&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
				<strong>안양대학교 입학처 홈페이지&nbsp;</strong>
				<span>바로가기</span>
				<!--화살표 이미지 코드 작성-->
			</a>
		</div>
		<div class="in-box01">
			<p class="in-con01">
				<span>교육부 3주기 대학기본역량진단</span><br>
				<strong>'일반재정지원대학'</strong>
				"선정"
			</p>
			<p class="in-con02">
				<span>교육부 2023년 교육국제화역량 인증제</span>
				<strong>'교육국제화역량 인증대학'</strong>
				"선정"
			</p>
			<p class="in-con03">
				<span>교육부 5주기 교원양성기관역량진단</span>
				<strong>'최우수 A등급'</strong>
				"획득"
			</p>
		</div>
		<div class="in-box02">
			<a class="in-link03" href="https://enter.anyang.ac.kr/enter/early/notice.do?mode=view&amp;articleNo=27229&amp;article.offset=0&amp;articleLimit=10" target="_blank" title="새창바로가기">
				<p style="color: rgb(183, 240, 177);">
					<strong>대학입학전형시행계획 주요사항</strong>
				</p>2025학년도<!--span>바로가기</span-->
			</a>
			<a class="in-link03" href="https://enter.anyang.ac.kr/enter/expatriate/notice.do?mode=view&amp;articleNo=27234&amp;article.offset=0&amp;articleLimit=10&amp;srCategoryId=14" target="_blank" title="새창바로가기">
				<p style="color: rgb(209, 178, 255);">
					<strong>재외국민과 외국인 주요사항</strong>
				</p>2025학년도<!--span>바로가기</span-->
			</a>
			<a class="in-link06" href="https://cs.u-is.co.kr/anyang/intro.htm" target="_blank" title="새창바로가기">
				<p style="color: rgb(255, 193, 158);">
					<strong>입학 성적산출</strong>
				</p>3개년 입시결과<!--span>바로가기</span-->
			</a>
			<a class="in-link07" href="https://enter.anyang.ac.kr/enter/counseling/ask-and-answer.do" target="_blank" title="새창바로가기">
				<p style="color: rgb(250, 237, 125);">
					<strong>입학 상담문의</strong>
				</p>묻고 답하기<!--span>바로가기</span-->
			</a>
			<a class="in-link05" href="https://enter.anyang.ac.kr/enter/early/notice.do?mode=view&amp;articleNo=19656&amp;article.offset=0&amp;articleLimit=10" target="_blank" title="새창바로가기">
				<p style="color: rgb(178, 235, 244);">
					<strong>전과제도 안내</strong>
				</p>신입학<!--span>바로가기</span-->
			</a>
		</div>
	</div>
</body>
</html>
