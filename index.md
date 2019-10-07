## BINGO PAGE

You can use the [editor on GitHub](https://github.com/leebingoo/leebingo.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/leebingoo/leebingo.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.


<!doctype html>
<html lang="ko">
<head>
<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta property='og:title' content="현대자동차 DOgNOR 헌혈카 캠페인">
<meta property='og:site_name' content="www.iamdognor.com/">
<meta property='og:description' content="반려견 헌혈을 위해 현대자동차 DOgNOR 헌혈카가 전국 곳곳으로 달려갑니다">
<meta property='og:url' content="https://www.iamdognor.com/">
<meta property='og:image' content="https://www.iamdognor.com/static/img/common/sns_1200x630.jpg">

<title>현대자동차 반려견 헌혈카 캠페인</title>
<script src="static/js/jquery-1.11.3.min.js"></script>
<script src="static/js/common.js"></script>
<script src="static/js/apply.js"></script>

<script type="text/javascript" src="/static/js/util.js?v=1"></script>
<script type="text/javascript" src="/static/js/site.js?v=1"></script>
<script type="text/javascript" src="/static/js/applyapp.js?v=1"></script>
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-148342669-1"></script>
<script type="text/javascript" src="static/js/googleTag.js"></script>

<script type="text/javascript" src="/static/js/redirect.js"></script>
<link rel="stylesheet" href="static/css/common.css">
<link rel="stylesheet" href="static/css/apply.css">
<script>
/* 섹렉트 박스 선택 정보 변경 - 불필요시 삭제*/
$(function(){
	 var selectTarget = $('span.select_list select'); 
	 
	selectTarget.change(function(){ 
		 var select_name = $(this).children('option:selected').text(); 
		 $(this).siblings('label').text(select_name); 
	}); 
});
</script>
</head>
<body>
	<!-- [s] wrap -->
	<div id="wrap">
		<!-- [s] header -->
		<header>
			<h1><a href="./" onclick="click_tag('Main Page', 'Main');">HYUNDAI</a></h1>
			
			<div class="gnb_frm">
				<ul id="gnb">
					<li class="gnb1">
						<a href="#">I’m DOgNOR 캠페인</a>
						<ul>
							<li><a href="#" data-name="intro" onclick="click_tag('Main Page', '메뉴 : 소개');">소개</a></li>
						</ul>
					</li>
					<li class="gnb2">
						<a href="#">I’m DOgNOR</a>
						<ul>
							<li><a href="#" data-name="apply" onclick="click_tag('반려견 헌혈 신청하기', '헌혈 신청하기');">반려견 헌혈 신청하기</a></li>
							<li><a href="#" data-name="tour_course" onclick="click_tag('13주간의 헌혈카 투어코스', '13주간의 헌혈카 투어코스');">13주간의 헌혈카 투어 코스</a></li>
							<li><a href="#" data-name="hall_of_fame" onclick="click_tag('DogNor 명예의 전당', 'DogNor 명예의 전당');">DOgNOR 명예의 전당</a></li>
						</ul>
					</li>
					<li class="gnb3">
						<a href="#">I’m Supporter</a>
						<ul>
							<li><a href="#" data-name="cheering_event" onclick="click_tag('DogNor 응원해요', 'DOgNOR 응원해요');">DOgNOR 응원해요</a></li>
							<li><a href="#" data-name="sharing_event" onclick="click_tag('DogNor 영상 공유해요', 'DogNor 영상 공유해요');">DOgNOR 영상 공유해요</a></li>
						</ul>
					</li>
					<li class="gnb4">
						<a href="#">Notice</a>
						<ul>
							<li><a href="#" data-name="notice" onclick="click_tag('공지사항', '공지사항');">공지사항</a></li>
							<li><a href="#" data-name="faq" onclick="click_tag('FAQ', 'FAQ');">FAQ</a></li>
						</ul>
					</li>
				</ul>
			</div>

			<button type="button" id="siteMapBtn" >
				<span>전체메뉴 열기</span>
			</button>
		</header>
		<!-- [e] header -->

		<!-- [s] 전체 메뉴 -->
		<div id="siteMapFrm">
			<div class="sitemap_inner">
				<div class="sitemap_box">
					<div class="sitemap_blk">
						<span class="tit">I’m DOgNOR 캠페인</span>
						<ul>
							<li><a href="#" data-name="intro" onclick="click_tag('Main Page', '메뉴 : 소개');">소개</a></li>
						</ul>
					</div>
					<div class="sitemap_blk">
						<span class="tit">I’m DOgNOR</span>
						<ul>
							<li><a href="#" data-name="apply" onclick="click_tag('반려견 헌혈 신청하기', '헌혈 신청하기');">반려견 헌혈 신청하기</a></li>
							<li><a href="#" data-name="tour_course" onclick="click_tag('13주간의 헌혈카 투어코스', '13주간의 헌혈카 투어코스');">13주간의 헌혈카 투어 코스</a></li>
							<li><a href="#" data-name="hall_of_fame" onclick="click_tag('DogNor 명예의 전당', 'DogNor 명예의 전당');">DOgNOR 명예의 전당</a></li>
						</ul>
					</div>
					<div class="sitemap_blk">
						<span class="tit">I’m Supporter</span>
						<ul>
							<li><a href="#" data-name="cheering_event" onclick="click_tag('DogNor 응원해요', 'DOgNOR 응원해요');">DOgNOR 응원해요</a></li>
							<li><a href="#" data-name="sharing_event" onclick="click_tag('DogNor 영상 공유해요', 'DogNor 영상 공유해요');">DOgNOR 영상 공유해요</a></li>
						</ul>
					</div>
					<div class="sitemap_blk">
						<span class="tit">Notice</span>
						<ul>
							<li><a href="#" data-name="notice" onclick="click_tag('공지사항', '공지사항');">공지사항</a></li>
							<li><a href="#" data-name="faq" onclick="click_tag('FAQ', 'FAQ');">FAQ</a></li>
						</ul>
					</div>
				</div>
				<button type="button" id="btnSitemapClose"><img src="static/img/common/btn_close.png" alt="닫기"></button>
			</div>
		</div>
		<!-- [e] 전체 메뉴 -->

		<div id="container">
			<div class="content">
				<!-- [s] content -->
				<!-- [s] 신청하기 sec_1 -->
				<div class="frm sec_1">
					<div class="inner">
						<div class="txt_box">
							<h2>반려견 헌혈 신청하기</h2>
							<p>
                                체중 25kg 이상 2~8세,<br>
                                정기적인 심장 사상충 및 내외부 구충 예방, 종합백신 예방접종을 실시한 반려견만 신청 가능합니다.<br>
                                13주간 각 지역별 헌혈카 운영 장소에서 만날 용감한 예비 도그너를 기다리겠습니다.
                            </p>
						</div>
						<div class="txt_box">
							<h3>용감한 도그너를 위한 선물</h3>
							<img src="static/img/apply/img_campaign_gift.png" alt="도그너 라이선스, 도그너 에코백, 도그너 조끼, 도그너 스카프">
						</div>
					</div>
				</div>
				<!-- [e] 신청하기 sec_1 -->
				<!-- [s] 신청하기 sec_2 -->
				<div class="frm sec_2">
					<div class="inner">
						<div class="txt_box">
							<h3>헌혈 참여 프로세스</h3>
							<p> 지역별 일정에 맞춰 도그너 헌혈카가 찾아갑니다!</p>
							<img src="static/img/apply/ico_application_step.png" alt="">
                            <div class="ir">
                                <ul>
                                    <li>온라인 헌혈 신청</li>
                                    <li>사전 유선 상담</li>
                                    <li>헌혈카 방문</li>
                                    <li>채혈/기초 검사</li>
                                    <li>헌혈</li>
                                    <li>리워드 제공 (검진 결과 + 헌혈증 발급)</li>
                                </ul>
                            </div>
						</div>
					</div>
				</div>
				<!-- [e] 신청하기 sec_2 -->
				<!-- [s] 신청하기 sec_3 -->
				<div class="frm sec_3">
					<div class="inner">
						<div class="txt_box">
							<h3>헌혈 신청하기</h3>
							<ul class="step_indi">
								<li class="on">1</li>
								<li>2</li>
								<li>3</li>
							</ul>
						</div>
						<!-- [s] 신청서 작성 입력 폼 -->
						<form id="app_form" class="app_form">
							<ul>
								<!-- [S]신청서 작성 1 -->
								<li class="on">
									<ul>
										<li>
											<p class="tit">보호자 기본정보</p>
											<table>
												<tbody>
													<tr>
														<td>
															<div class="ipt_blk">
																<label for="app_name">보호자 이름</label>
																<input type="text" id="app_name" maxlength="20">
															</div>
														</td>
														<td>
															<div class="ipt_blk">
																<label for="app_phone">기본 연락처</label>
																<input type="text" id="app_phone" maxlength="11">
															</div>
														</td>
														<td>
															<div class="ipt_blk">
																<label for="app_e_phone">비상 연락처</label>
																<input type="text" id="app_e_phone" maxlength="11">
															</div>
														</td>
													</tr>
													<tr>
														<td colspan="3">
															<div class="ipt_blk full">
																<label for="app_email">메일 주소</label>
																<input type="text" id="app_email">
															</div>
														</td>
													</tr>
													<tr>
														<td class="post_find">
															<div class="ipt_blk post">
																<label for="app_post">우편 번호</label>
																<input type="text" id="app_post" class="app_post"readonly>
																<button type="button" onclick="execDaumPostcode()" class="btn_post"><img src="static/img/apply/ico_post_find.png" alt=""></button>
															</div>
														</td>
														<td colspan="2">
															<div class="ipt_blk two_part ">
																<label for="app_address" readonly>주소</label>
																<input type="text" id="app_address">
															</div>
														</td>
													</tr>
													<tr>
														<td colspan="3">
															<div class="ipt_blk full">
																<label for="app_d_address">상세 주소</label>
																<input type="text" id="app_d_address">
															</div>
														</td>
													</tr>
												</tbody>
											</table>
										</li>
										<li>
											<p class="tit">DOgNOR 기본 정보</p>
											<table>
												<tbody>
													<tr>
														<td colspan="2">
															<div class="ipt_blk half">
																<label for="app_dg_name">DOgNOR 이름</label>
																<input type="text" id="app_dg_name" maxlength="50">
															</div>
														</td>
													</tr>
													<tr>
														<td class="photo_upload">
															<div class="ipt_blk half photo">
																<div class="no_label">사진</div>
																<input class="c_upload_input" id="dog_org_picture" value="" placeholder="파일선택" readonly>
																<input type="hidden" name="dog_picture" id="dog_picture" value="">
																<label for="app_dg_photo" class="btn_filebox"></label>
   																<input type="file" class="app_dg_photo" id="app_dg_photo" name="file">
															</div>
														</td>
														<td>
															<div class="ipt_text">
																※ 최근 3개월 이내 촬영된 사진 (10MB 이하) 
															</div>
														</td>
													</tr>
													<tr>
														<td class="select_box">
															<div class="ipt_blk half">
																<div class="no_label">견종</div>
																<span class="select_list">
																	<label for="app_dg_list">선택해주세요</label>
																	<select id="app_dg_list">
																		
																	</select>
																</span>
															</div>
														</td>
														<td class="dg_etc">
															<div class="ipt_blk half">
																<label for="app_dg_etc">기타 견종</label>
																<input type="text" id="app_dg_etc" value="">
															</div>
														</td>
													</tr>
													<tr>
														<td>
															<div class="radio_blk half">
																<div class="no_label">성별</div>
																<span>
																	<input type="radio" name="app_dg_sex" id="app_dg_sex_m" value="M">
																	<label for="app_dg_sex_m">수컷<img src="static/img/apply/ico_sex_1.png" alt=""></label>
																</span>
																<span>
																	<input type="radio" name="app_dg_sex" id="app_dg_sex_f" value="F">
																	<label for="app_dg_sex_f">암컷<img src="static/img/apply/ico_sex_2.png" alt=""></label>
																</span>
															</div>
														</td>
														<td>
															<div class="radio_blk half">
																<div class="no_label">중성화</div>
																<span>
																	<input type="radio" name="app_dg_neu" id="app_dg_neu_y" value="Y">
																	<label for="app_dg_neu_y">예</label>
																</span>
																<span>
																	<input type="radio" name="app_dg_neu" id="app_dg_neu_n" value="N">
																	<label for="app_dg_neu_n">아니요</label>
																</span>
															</div>
														</td>
													</tr>
													<tr>
														<td class="select_box">
															<div class="ipt_blk half">
																<div class="no_label">년생</div>
																<span class="select_list">
																	<label for="app_dg_old">선택해주세요</label>
																	<select id="app_dg_old">
																		
																	</select>
																</span>
															</div>
														</td>
														<td>
															<div class="ipt_blk half">
																<label for="app_dg_kg">몸무게(kg)</label>
																<input type="text" id="app_dg_kg">
															</div>
														</td>
													</tr>
												</tbody>
											</table>
										</li>
										<li>
											<p class="tit">헌혈 희망 지역 및 일정
												<a href="javascript:;" class="btn_q_pop" onclick="front.toggleTooltip('#qlocalPopup');" ><img src="static/img/apply/ico_question.png" alt=""></a>
											</p>
											<table>
												<tbody>
													<tr>
														<td class="select_box">
															<div class="ipt_blk half">
																<div class="no_label">지역</div>
																<span class="select_list">
																	<label for="app_dg_loc">선택해주세요</label>
																	<select id="app_dg_loc">
																		
																	</select>
																</span>
															</div>
														</td>
														<td class="select_box">
															<div class="ipt_blk half">
																<div class="no_label">일정</div>
																<span class="select_list">
																	<label for="app_dg_date">선택해주세요</label>
																	<select id="app_dg_date">
																		
																	</select>
																</span>
															</div>
														</td>
													</tr>
												</tbody>
											</table>
											<!-- [s] 헌혈 희망 지역 및 일정 팝업 -->
											<div id="qlocalPopup" class="tooltipPop">
												<div class="Popup_h">
													아래 헌혈카 방문 일정을 참고하셔서 지역과 일시를 선택해주세요.
													<button type="button" class="btn_close" onclick="front.toggleTooltip('#qlocalPopup');"><img src="static/img/apply/btn_tooltip_close.png" alt="닫기"></button>
												</div>
												<table class="qlocalPopup_table">
													<tbody>
														<tr>
															<td>
																<div>
																	<p>
																		<span><span>10월 6일 (일)</span> - 서울특별시</span><br>
																		<span><span>10월 13일 (일)</span> - 강원도</span><br>
																		<span><span>10월 23일 (수)</span> - 서울특별시</span><br>
																		<span><span>10월 27일 (일)</span> - 경기도</span>
																	</p>
																</div>
																<div>
																	<p>
																		<!--span><span>11월 9일 (토)</span> - 서울특별시</span><br-->
																		<span><span>11월 14일 (목)</span> - 인천광역시</span><br>
																		<span><span>11월 20일 (수)</span> - 경기도</span><br>
																		<span><span>11월 24일 (일)</span> - 충청도</span>
																	</p>
																</div>
																<div>
																	<p>
																		<span><span>12월 4일 (수)</span> - 충청도</span><br>
																		<span><span>12월 8일 (일)</span> - 전라도</span><br>
																		<!--span><span>12월 18일 (수)</span> - 전라도</span><br-->
																		<span><span>12월 22일 (일)</span> - 경상도</span><br>
																		<span><span>12월 29일 (일)</span> - 경상도</span>
																	</p>
																</div>
															</td>
														</tr>
													</tbody>
												</table>
											</div>
											<!-- [e] 헌혈 희망 지역 및 일정 팝업 -->
										</li>
									</ul>
									<span class="btn_step_box">
										<a href="javascript:;" class="btn_next_step" data-idx="1" onclick="click_tag('반려견 헌혈 신청하기', '다음으로 1');">다음으로</a>
									</span>
								</li>
								<!-- [e]신청서 작성 1 -->
								<!-- [S]신청서 작성 2 -->
								<li class="">
									<ul>
										<li >
											<p class="tit">접종/검사 여부</p>
											<table>
												<tbody>
													<tr>
														<td>
															<div class="radio_blk half">
																<div class="no_label">예방접종</div>
																<span>
																	<input type="radio" name="app_dg_inje" id="app_dg_inje_y" value="Y">
																	<label for="app_dg_inje_y">예</label>
																</span>
																<span>
																	<input type="radio" name="app_dg_inje" id="app_dg_inje_n" value="N">
																	<label for="app_dg_inje_n">아니요</label>
																</span>
															</div>
														</td>
														<td>
															<div class="radio_blk half">
																<div class="no_label">부스팅
																	<a href="javascript:;" class="btn_q_pop" onclick="front.toggleTooltip('#qbstPopup');"><img src="static/img/apply/ico_question.png" alt=""></a>
																</div>
																<span>
																	<input type="radio" name="app_dg_bs" id="app_dg_bs_y" value="Y">
																	<label for="app_dg_bs_y">예</label>
																</span>
																<span>
																	<input type="radio" name="app_dg_bs" id="app_dg_bs_n" value="N">
																	<label for="app_dg_bs_n">아니요</label>
																</span>
																<!-- [s] 부스팅 튤팁 -->
																<div id="qbstPopup" class="tooltipPop">
																	<button type="button" class="btn_close" onclick="front.toggleTooltip('#qbstPopup');"><img src="static/img/apply/btn_tooltip_close_b.png" alt="닫기"></button>
																	<table>
																		<tbody>
																			<tr>
																				<td class="txt_tit">
																					부스팅
																				</td>
																				<td class="txt_sub">
																					보강접종이라고도 하며, 5차까지 기초 예방접종이 완료된 반려견들을<br>
                                                                                    대상으로 매년 1회 접종하는 과정<br>
																					예방 접종 이후에 항체가 생성되더라도 시간이 지나면서 항체의 양이<br> 
																					줄어드는데, 부스팅을 하면 항체의 양이 다시 증가되면서 면역 수준을<br> 
																					유지하는 데 도움이 됨
																				</td>
																			</tr>
																		</tbody>
																	</table>
																</div>
																<!-- [e] 부스팅 튤팁 -->
															</div>
														</td>
													</tr>
													<tr>
														<td class="td_on_off_btn">
															<div class="radio_blk half">
																<div class="no_label">심장사상충 검사</div>
																<span>
																	<input type="radio" name="app_dg_insp" id="app_dg_insp_y" value="Y">
																	<label for="app_dg_insp_y">예</label>
																</span>
																<span>
																	<input type="radio" name="app_dg_insp" id="app_dg_insp_n" value="N">
																	<label for="app_dg_insp_n">아니요</label>
																</span>
															</div>
														</td>
														<td class="td_on_off_blk">
															<div class="ipt_blk half">
																<label for="app_insp_recent">최근 검사일</label>
																<input type="text" id="app_insp_recent">
															</div>
															<div class="ipt_blk_noti">※ 심장사상충 최근 검사일을 (년/월)로 기입해주세요</div>
														</td>
													</tr>
												</tbody>
											</table>
										</li >
										<li class="terms_nec">
											<p class="tit">필수 병력 정보
												<a href="javascript:;" class="btn_q_pop" onclick="front.toggleTooltip('#qnecPopup');"><img src="static/img/apply/ico_question.png" alt=""></a>
											</p>
											<span class="sub_tit">아래 질병 병력이 있으면&nbsp;&nbsp;<img class="ico_tit_chk" src="static/img/apply/ico_chk.png" alt="">로 체크해주세요</span>
											<table>
												<tbody>
													<tr>
														<td>
															<div class="chk_box full">
																<span class="chk_blk">
																	<input type="checkbox" id="app_dg_prev_1" value="01">
																	<label for="app_dg_prev_1">심장사상충</label>
																</span>
																<span class="chk_blk">
																	<input type="checkbox" id="app_dg_prev_2" value="02">
																	<label for="app_dg_prev_2">라임병</label>
																</span>
																<span class="chk_blk">
																	<input type="checkbox" id="app_dg_prev_3" value="03">
																	<label for="app_dg_prev_3">록키산홍반열</label>
																</span>
																<span class="chk_blk">
																	<input type="checkbox" id="app_dg_prev_4" value="04">
																	<label for="app_dg_prev_4">진드기 매개 질병</label>
																</span>
															</div>
														</td>
													</tr>
													<tr class="terms_h">
														<td>
															<div class="field_box">
																<p class="tit_h">기타 진드기 매개 질병 선택 혹은 다른 병력 있을 시 기입해주세요</p>
																<p class="txt_input"><input type="text" id="etc_medical"></p>
															</div>
														</td>
													</tr>
													<tr class="terms_h">
														<td>
															<div class="field_box">
																<p class="tit_h"><span>복약 정보</span> - 현재 복용 중인 약이 있다면 기입해주세요</p>
																<p class="txt_input"><input type="text" id="drug_info"></p>
															</div>
														</td>
													</tr>
												</tbody>
											</table>
											<!-- [s] 필수 병력 정보 튤팁 -->
											<div id="qnecPopup" class="tooltipPop">
												<button type="button" class="btn_close" onclick="front.toggleTooltip('#qnecPopup');"><img src="static/img/apply/btn_tooltip_close_b.png" alt="닫기"></button>
												<table>
													<tbody>
														<tr>
															<tr>
																<td class="txt_tit">
																	심장 사상충
																</td>
																<td class="txt_sub">
																	심장 사상충이란 강아지의 심장과 폐혈관에 기생하는 기생충으로, 주로 모기에 의해 감염<br>
																	감염 후 증상이 악화되면 우심부전까지 이어질 수 있는 위험한 질병으로 매달 예방을 하는 것을 추천
																</td>
															</tr>
															<tr>
																<td class="txt_tit">
																	라임병
																</td>
																<td class="txt_sub">
																	라임병은 진드기 매개 질병으로, 진드기가 무는 과정에서 보렐리아균이 신체에 침범하여<br> 
																	혈류를 타고 여러 장기에 감염되는 질병이며 열, 무기력, 식욕감퇴, 절뚝거림부터 부정맥, 신경 징후,<br>  
																	관절염 및 신장 손상과 같은 증상까지 악화될 수 있는 병<br> 
																	강아지에서 사람으로 옮기는 질병은 아니나, 사람 역시 진드기에 물리게 될 경우,<br> 
																	보렐리아균에 감염되면서 라임병이 발생할 수 있음
																</td>
															</tr>
															<tr>
																<td class="txt_tit">
																	록키산홍반열
																</td>
																<td class="txt_sub">
																	발진성 열병으로 진드기 침에 의해 매개되는 리케차에 의하여 발병됨<br>
																	감염된 강아지는 식욕이 떨어지고, 열이 나며, 기침, 복통, 구토, 설사, 얼굴 혹은 다리 부종, 빈혈 및<br> 
																	혈소판 감소 등의 증상을 보이며, 라임병과 마찬가지로 사람에게 옮기는 질병은 아니나,<br> 
																	사람도 진드기를 통해 감염될 가능성 있음
																</td>
															</tr>
															<tr>
																<td class="txt_tit">
																	진드기 매개 질병
																</td>
																<td class="txt_sub">
																	진드기는 라임병, 록키산홍반열 이외에도 애를리키아증 등 심각한 질병의 원인이 되며,<br> 
																	사람과 반려동물 모두 발병 가능성 있음<br>
																	예방이 최선의 방법이지만, 이미 진드기 매개 질병이 발견됐다면 초기 제거가 중요<br>
																</td>
															</tr>
														</tr>
													</tbody>
												</table>
											</div>
											<!-- [e] 필수 병력 정보 튤팁 -->
										</li>
										<li class="terms_full">
											<p class="tit">수혈/헌혈 경험</p>
											<table>
												<tbody>
													<tr class="terms_f">
														<td class="tr_on_off_btn"> 
															<div class="radio_blk full">
																<div class="no_label">1. 수혈을 받은 적이 있다</div>
																<div class="radio_box">
																	<span>
																		<input type="radio" name="app_dg_trans" id="app_dg_trans_y" value="Y">
																		<label for="app_dg_trans_y">예</label>
																	</span>
																	<span>
																		<input type="radio" name="app_dg_trans" id="app_dg_trans_n" value="N">
																		<label for="app_dg_trans_n">아니요</label>
																	</span>
																</div>
															</div>
														</td>
													</tr>
													<tr class="terms_h tr_on_off_blk">
														<td>
															<div class="field_box">
																<p class="tit_h">1-(1) 예로 대답한 경우, 수혈의 이유와 시기를 기입해주세요</p>
																<p class="txt_input"><input type="text" id="blood_transfusion_reason" value=""></p>
															</div>
														</td>
													</tr>
													<tr class="terms_f">
														<td class="tr_on_off_btn">
															<div class="radio_blk full">
																<div class="no_label">2. 헌혈을 한 적이 있다</div>
																<div class="radio_box">
																	<span>
																		<input type="radio" name="app_dg_trans_b" id="app_dg_trans_b_y" value="Y">
																		<label for="app_dg_trans_b_y">예</label>
																	</span>
																	<span>
																		<input type="radio" name="app_dg_trans_b" id="app_dg_trans_b_n" value="N">
																		<label for="app_dg_trans_b_n">아니요</label>
																	</span>
																</div>
															</div>
														</td>
													</tr>
													<tr class="terms_h tr_on_off_blk">
														<td>
															<div class="field_box">
																<p class="tit_h">2-(1) 예로 대답한 경우, 가장 최근 헌혈 시기를 기입해주세요</p>
																<p class="txt_input"><input type="text" id="blood_donation_reason" value=""></p>
															</div>
														</td>
													</tr>
												</tbody>
											</table>
										</li>
										<li class="terms_full">
											<p class="tit">기타 의료 정보</p>
											<table>
												<tbody>
													<tr class="terms_f">
														<td class="tr_on_off_btn">
															<div class="radio_blk full">
																<div class="no_label">1. 알러지 반응이 있는 특정 약물이 있나요?</div>
																<div class="radio_box">
																	<span>
																		<input type="radio" name="app_dg_mcal_info_1" id="app_dg_mcal_info_1_y" value="Y">
																		<label for="app_dg_mcal_info_1_y">예</label>
																	</span>
																	<span>
																		<input type="radio" name="app_dg_mcal_info_1" id="app_dg_mcal_info_1_n" value="N">
																		<label for="app_dg_mcal_info_1_n">아니요</label>
																	</span>
																</div>
															</div>
														</td>
													</tr>
													<tr class="terms_h tr_on_off_blk">
														<td>
															<div class="field_box">
																<p class="tit_h">1-(1) 예로 체크한 경우, 구체적인 약물 명을 기입해주세요</p>
																<p class="txt_input"><input type="text" id="allergy_drug_name"></p>
															</div>
														</td>
													</tr>
													<tr class="terms_f">
														<td>
															<div class="radio_blk full">
																<div class="no_label">2. 입질 여부</div>
																<div class="radio_box">
																	<span>
																		<input type="radio" name="app_dg_mcal_info_2" id="app_dg_mcal_info_2_y" value="Y">
																		<label for="app_dg_mcal_info_2_y">예</label>
																	</span>
																	<span>
																		<input type="radio" name="app_dg_mcal_info_2" id="app_dg_mcal_info_2_n" value="N">
																		<label for="app_dg_mcal_info_2_n">아니요</label>
																	</span>
																</div>
															</div>
														</td>
													</tr>
													<tr class="terms_f">
														<td>
															<div class="radio_blk full">
																<div class="no_label">3. 삭모기(클리퍼)에 민감하게 반응하나요? </div>
																<div class="radio_box">
																	<span>
																		<input type="radio" name="app_dg_mcal_info_3" id="app_dg_mcal_info_3_y" value="Y">
																		<label for="app_dg_mcal_info_3_y">예</label>
																	</span>
																	<span>
																		<input type="radio" name="app_dg_mcal_info_3" id="app_dg_mcal_info_3_n" value="N">
																		<label for="app_dg_mcal_info_3_n">아니요</label>
																	</span>
																</div>
															</div>
														</td>
													</tr>
													<tr class="terms_f">
														<td class="tr_on_off_btn">
															<div class="radio_blk full">
																<div class="no_label">4. 털을 삭모할 때 민감하게 반응하는 신체 부위가 있나요?</div>
																<div class="radio_box">
																	<span>
																		<input type="radio" name="app_dg_mcal_info_4" id="app_dg_mcal_info_4_y" value="Y">
																		<label for="app_dg_mcal_info_4_y">예</label>
																	</span>
																	<span>
																		<input type="radio" name="app_dg_mcal_info_4" id="app_dg_mcal_info_4_n" value="N">
																		<label for="app_dg_mcal_info_4_n">아니요</label>
																	</span>
																</div>
															</div>
														</td>
													</tr>
													<tr class="terms_h tr_on_off_blk">
														<td>
															<div class="field_box">
																<p class="tit_h">4-(1) 예로 체크한 경우, 신체 부위를 기입해주세요</p>
																<p class="txt_input"><input type="text" id="shearing_part_name"></p>
															</div>
														</td>
													</tr>
													<tr class="terms_f">
														<td>
															<div class="radio_blk full">
																<div class="no_label">5. 심장사상충 예방은 매달 하시나요?</div>
																<div class="radio_box">
																	<span>
																		<input type="radio" name="app_dg_mcal_info_5" id="app_dg_mcal_info_5_y" value="Y">
																		<label for="app_dg_mcal_info_5_y">예</label>
																	</span>
																	<span>
																		<input type="radio" name="app_dg_mcal_info_5" id="app_dg_mcal_info_5_n" value="N">
																		<label for="app_dg_mcal_info_5_n">아니요</label>
																	</span>
																</div>
															</div>
														</td>
													</tr>
												</tbody>
											</table>
										</li>
									</ul>
									<span class="btn_step_box">
										<a href="javascript:;" class="btn_prev_step" data-idx="0" >이전으로</a>
										<a href="javascript:;" class="btn_next_step" data-idx="2" onclick="click_tag('반려견 헌혈 신청하기', '다음으로 2');">다음으로</a>
									</span>
								</li>
								<!-- [e]신청서 작성 2 -->
								<!-- [S]신청서 작성 3 -->
								<li class="">
									<ul>
										<li class="terms_full">
											<p class="tit center">
												반려견 헌혈 참여를 위한 모든 필요 정보를 기입하셨습니다.<br>
												신청 접수 완료를 위해 필수 안내 사항을 읽으시고 동의 버튼을 눌러주세요.
											</p>
											<table>
												<tbody>
													<tr class="terms_h terms_f">
														<td>
															<div class="radio_blk full">
																<div class="no_label">헌혈 신청에 따른 필수 안내 사항 <span>(동의 필수)</span></div>
																<div class="radio_box">
																	<span>
																		<input type="radio" name="app_dg_terms_1" id="app_dg_terms_1_y">
																		<label for="app_dg_terms_1_y">예</label>
																	</span>
																	<span>
																		<input type="radio" name="app_dg_terms_1" id="app_dg_terms_1_n">
																		<label for="app_dg_terms_1_n">아니요</label>
																	</span>
																</div>
															</div>
															<div class="field_box">
																<p>
																	1. 헌혈 과정과 관련하여 클리퍼로 인한 자극, 국소 염증, 드물게 정맥 열상, 피하출혈 및 혈종, 오심, 현기증 등의 위험성이 있습니다.<br>
																	2. 헌혈 과정에 참여한 의료진은 직접적으로 헌혈 과정과 관련되지 않은 질병 및 상처나 사고에 대하여 치료를 할 책임이 없습니다.<br>
																	3. 헌혈 혈액의 이상 발견 시 혈액 제품의 품질 관리를 위하여 혈액은 폐기될 수 있습니다.<br>
																	4. 헌혈견이 헌혈 과정에서 심하게 흥분하여 진정이 필요한 경우 헌혈견의 안전을 위하여 무리하게 헌혈을 진행하지 않고 중단할 수 있습니다.<br>
																	5. 성공적으로 헌혈이 이루어지더라도, 혈액 제품의 유효기간 중 혈액의 수요가 없으면 혈액 제품의 품질 관리를 위해 유효기간이 지나면 
																	폐기될 예정입니다.
																</p>
															</div>
														</td>
													</tr>
													<tr class="terms_h terms_f">
														<td>
															<div class="radio_blk full">
																<div class="no_label">개인정보 취급 및 위탁 동의 <span>(동의 필수)</span></div>
																<div class="radio_box">
																	<span>
																		<input type="radio" name="app_dg_terms_2" id="app_dg_terms_2_y">
																		<label for="app_dg_terms_2_y">예</label>
																	</span>
																	<span>
																		<input type="radio" name="app_dg_terms_2" id="app_dg_terms_2_n">
																		<label for="app_dg_terms_2_n">아니요</label>
																	</span>
																</div>
															</div>
															<div class="field_box">
																<p>
																	1. 수탁자 : 현대자동차㈜, 이노션월드와이드, ㈜더브리즈<br>
																	2. 목적 : DOgNOR 참여 여부 확인 및 CS 처리<br>
																	3. 항목 : 보호자 휴대폰 번호 및 상세 정보, 헌혈견 기본 정보 및 건강 정보<br><br>

																	* 보유 및 이용 기간 : 캠페인 종료 후, 고객 응대 등을 위하여 3개월 간 보관 후 지체 없이 파기.<br>
																	단 고객으로부터 동의를 얻었거나 법령상 일정 기간 보관할 의무가 있는 경우에는 그 기간 동안 보유할 수 있습니다.
																</p>
															</div>
														</td>
													</tr>
												</tbody>
											</table>
										</li>
									</ul>
									<span class="btn_step_box">
										<a href="javascript:;" class="btn_prev_step" data-idx="1">이전으로</a>
										<a href="javascript:;" class="btn_next_step" data-idx="3" id="btn_enter" onclick="click_tag('반려견 헌혈 신청하기', '헌혈 신청완료');">헌혈 접수 완료하기</a>
									</span>
								</li>
								<!-- [e]신청서 작성 3 -->
							</ul>
						</form>
						<!-- [e] 신청서 작성 입력 폼 -->
					</div>
				</div>
				<!-- [e] 신청하기 sec_3 -->
				<!-- [e] content -->

				<!-- [s] 퀵메뉴 -->
				<ul id="quickMenu">
					<li>
						<a href="apply.html?skip=true" class="btn1 on" onclick="click_tag('Main Page', '도그너 헌혈하기');">
							<span class="tit">I'm DOgNOR</span>
							<img src="static/img/common/bg_quick1.png" class="img" alt="">
							<span class="txt">
								반려견 헌혈에 관심 있고<br>
								지원 자격을 충족한다면,<br>
								지금 바로 신청하세요!
							</span>
							<span class="btn_blk">반려견 헌혈 신청</span>
						</a>
					</li>
					<li>
						<a href="javascript:;" onclick="front.pageLink('cheering_event'); click_tag('Main Page', '서포터 참여하기');" class="btn2 on">
							<span class="tit">I'm Supporter</span>
							<img src="static/img/common/bg_quick2.png" class="img" alt="">
							<span class="txt">
								반려견 헌혈 히어로인<br>
								도그너를 응원하면,<br>
								한정판 이모티콘을 드려요!									
							</span>
							<span class="btn_blk" >도그너 응원해요</span>
						</a>
					</li>
				</ul>
				<!-- [e] 퀵메뉴 -->
			</div>
		</div>

		<footer>
			<img src="static/img/common/logo_footer.png" class="logo" alt="로고">
			<div class="footer_inner">
				<div class="lft_box">
					<div class="copy_blk">
						<a href="terms.html" onclick="click_tag('이용약관', '이용약관');">이용약관</a>
						<span class="pipe">|</span>
						<a href="privacy.html" onclick="click_tag('개인정보 처리방침', '개인정보 처리방침');">개인정보 처리방침</a>
						<span class="copy">COPYRIGHT &copy; HYUNDAI MOTOR COMPANY.ALL RIGHTS RESERVED.</span>
					</div>
				</div>
				<div class="rgt_box">
					<a href="https://www.facebook.com/AboutHyundai" target="_blank" title="새창" onclick="click_tag('SNS 로고', '페이스북');"><img src="static/img/common/btn_fb.png" alt="페이스북"></a>
					<a href="https://www.youtube.com/user/AboutHyundai" target="_blank" title="새창" onclick="click_tag('SNS 로고', '유튜브');"><img src="static/img/common/btn_yt.png" alt="유튜브"></a>
					<a href="https://post.naver.com/abouthyundai" target="_blank" title="새창" onclick="click_tag('SNS 로고', '네이버 포스트');"><img src="static/img/common/btn_np.png" alt="네이버 포스트"></a>
					<a href="https://twitter.com/about_hyundai" target="_blank" title="새창" onclick="click_tag('SNS 로고', '트위터');"><img src="static/img/common/btn_tw.png" alt="트위터"></a>
					<a href="https://www.instagram.com/about_hyundai/" target="_blank" title="새창" onclick="click_tag('SNS 로고', '인스타그램');"><img src="static/img/common/btn_in.png" alt="인스타그램"></a>
				</div>
				<div class="bot_box">
					<a href="https://cafe.naver.com/kcbda2017" target="_blank" title="새창" onclick="click_tag('한국헌혈견협회', '한국헌혈견협회');"><img src="static/img/common/img_sponsor1.png" alt="">한국헌혈견협회</a>
					<a href="http://vmth.konkuk.ac.kr/" target="_blank" title="새창" onclick="click_tag('건국대학교 부속 동물병원', '건국대학교 부속 동물병원');"><img src="static/img/common/img_sponsor2.png" alt="">건국대학교 부속 동물병원</a>
				</div>
			</div>
		</footer>
	</div>
	<!-- [e] wrap -->

	<!-- [s] 접수 완료 팝업 -->
	<div id="app_end_Popup">
		<h4>
			<span id="dogName">반려견 이름</span>의 헌혈 신청이<br>
			접수되었습니다!
		</h4>
		<p class="sub_txt">
			운영 사무국에서 방문일시 관련해서 연락 드리겠습니다.<br>
			진행사항 관련해서 궁금하신 사항은 운영 사무국으로 연락주시기 바랍니다.<br>
			소중한 참여 감사합니다.
		</p>

		<button type="button" class="btn_submit" onClick="window.location.reload()">확 인</button>

		<div class="terms_footer_box">
			<div class="top_blk">
				DOgNOR는 유선 상담 및 내부 검토 후, 건강 상태 등을 확인하여 일정 별로 3-5 마리 선정될 예정입니다.<br>
				신청한 모든 반려견이 헌혈을 하기에는 장소적, 시간적 제약이 있는 점 양해 부탁드립니다.<br>
				<em>※ 주의 : 헌혈 2주 전부터 반려견은 예방접종을 할 수 없습니다.</em>
			</div>
			<div class="bot_blk">
				<p class="sub_txt_1">헌혈 신청 정보 수정 및 참여 취소를 원할 시, 운영 사무국으로 문의바랍니다.</p>
				<p class="sub_txt_2">이메일 : hyundai_iamdognor@innocean.com<span class="entity">&middot;</span>전화번호 : 031-535-5572</p>
			</div>
		</div>

		<button type="button" class="btn_close" onClick="window.location.reload()">닫기</button>
	</div>
	<!-- [e] 접수 완료 팝업 -->

	<!-- 우편번호 -->
	<div id="zip-layer" style="display:none;position:fixed;overflow:hidden;z-index:1;-webkit-overflow-scrolling:touch;">
		<img src="//t1.daumcdn.net/postcode/resource/images/close.png" id="btnCloseLayer" style="cursor:pointer;position:absolute;right:-3px;top:-3px;z-index:1" onclick="closeDaumPostcode()" alt="닫기 버튼">
		</div>		
			
		<script src="https://ssl.daumcdn.net/dmaps/map_js_init/postcode.v2.js"></script>
		<script>
			// 우편번호 찾기 화면을 넣을 element
			var element_layer = document.getElementById('zip-layer');
	
			function closeDaumPostcode() {
				// iframe을 넣은 element를 안보이게 한다.
				element_layer.style.display = 'none';
			}
	
			function execDaumPostcode() {
				new daum.Postcode({
					oncomplete: function(data) {
						// 검색결과 항목을 클릭했을때 실행할 코드를 작성하는 부분.
	
						// 각 주소의 노출 규칙에 따라 주소를 조합한다.
						// 내려오는 변수가 값이 없는 경우엔 공백('')값을 가지므로, 이를 참고하여 분기 한다.
						var addr = ''; // 주소 변수
						var extraAddr = ''; // 참고항목 변수
	
						//사용자가 선택한 주소 타입에 따라 해당 주소 값을 가져온다.
						if (data.userSelectedType === 'R') { // 사용자가 도로명 주소를 선택했을 경우
							addr = data.roadAddress;
						} else { // 사용자가 지번 주소를 선택했을 경우(J)
							// addr = data.jibunAddress;
							addr = data.roadAddress;
						}
	
						// 사용자가 선택한 주소가 도로명 타입일때 참고항목을 조합한다.
						if(data.userSelectedType === 'R'){
							// 법정동명이 있을 경우 추가한다. (법정리는 제외)
							// 법정동의 경우 마지막 문자가 "동/로/가"로 끝난다.
							if(data.bname !== '' && /[동|로|가]$/g.test(data.bname)){
								extraAddr += data.bname;
							}
							// 건물명이 있고, 공동주택일 경우 추가한다.
							if(data.buildingName !== '' && data.apartment === 'Y'){
								extraAddr += (extraAddr !== '' ? ', ' + data.buildingName : data.buildingName);
							}
							// 표시할 참고항목이 있을 경우, 괄호까지 추가한 최종 문자열을 만든다.
							if(extraAddr !== ''){
								extraAddr = ' (' + extraAddr + ')';
							}
							// 조합된 참고항목을 해당 필드에 넣는다.
							// document.getElementById("sample2_extraAddress").value = extraAddr;
						
						} else {
							// document.getElementById("sample2_extraAddress").value = '';
						}
	
						// 우편번호와 주소 정보를 해당 필드에 넣는다.
						document.getElementById('app_post').value = data.zonecode;
						document.getElementById("app_address").value = addr;
						// 커서를 상세주소 필드로 이동한다.
						document.getElementById("app_d_address").focus();
	
						// iframe을 넣은 element를 안보이게 한다.
						// (autoClose:false 기능을 이용한다면, 아래 코드를 제거해야 화면에서 사라지지 않는다.)
						element_layer.style.display = 'none';
					},
					width : '100%',
					height : '100%',
					maxSuggestItems : 5
				}).embed(element_layer);
	
				// iframe을 넣은 element를 보이게 한다.
				element_layer.style.display = 'block';
	
				// iframe을 넣은 element의 위치를 화면의 가운데로 이동시킨다.
				initLayerPosition();
			}
	
			// 브라우저의 크기 변경에 따라 레이어를 가운데로 이동시키고자 하실때에는
			// resize이벤트나, orientationchange이벤트를 이용하여 값이 변경될때마다 아래 함수를 실행 시켜 주시거나,
			// 직접 element_layer의 top,left값을 수정해 주시면 됩니다.
			function initLayerPosition(){
				var width = 600; //우편번호서비스가 들어갈 element의 width
				var height = 400; //우편번호서비스가 들어갈 element의 height
				var borderWidth = 2; //샘플에서 사용하는 border의 두께
	
				// 위에서 선언한 값들을 실제 element에 넣는다.
				element_layer.style.width = width + 'px';
				element_layer.style.height = height + 'px';
				element_layer.style.border = borderWidth + 'px solid';
				// 실행되는 순간의 화면 너비와 높이 값을 가져와서 중앙에 뜰 수 있도록 위치를 계산한다.
				element_layer.style.left = (((window.innerWidth || document.documentElement.clientWidth) - width)/2 - borderWidth) + 'px';
				element_layer.style.top = (((window.innerHeight || document.documentElement.clientHeight) - height)/2 - borderWidth) + 'px';
			}
		</script>		
</body>
</html>

