# 2021_wp_update

![alt text](https://github.com/JoshJong/2021_wp_update/blob/main/001-volunteer.png)

![alt text](https://github.com/JoshJong/2021_wp_update/blob/main/001-cms.png)


![alt text](https://github.com/JoshJong/2021_wp_update/blob/main/002-%E8%A1%8C%E7%82%BA%E6%BA%96%E5%89%87.png)

Update:
H1 display:flec / H1 font style / H1 Before After / H2 font style / H2 Before /Global linehight@min-width: 48em
mobile font layout adjustment

H1 @cms:
行為準則 <span class="h1_en">Code of Conduct</span>


@css:

part1---
/* line 49 ~ 152*/
/* Josh 2021 edited */
header.entry-header{
	display: flex;
    width: 100%;
	align-items: center;
    justify-content: center;
}
header.entry-header::before {
	content: url(http://wordcamptest.local/wp-content/themes/wctw2021/dest/img/h1-before.svg);
    display: inline-block;
	/*position: absolute;*/
	top: 0;
    height: auto;
    padding: 0em 1.8em;
}
header.entry-header::after {
	content: url(http://wordcamptest.local/wp-content/themes/wctw2021/dest/img/h1-after.svg);
    display: inline-block;
	/*position: absolute;*/
	top: 0;
    height: auto;
    padding: 0em 1.8em;

}

h1:not(.site-title):not(.home_info_title), h1.entry-title:not(:first-child), .page .panel-content .entry-title, .page-title, body.page:not(.twentyseventeen-front-page) .entry-title, .site-footer .widget-column.footer-widget-1 h2.widget-title {
	/*background-color: #0068b6;*/
	/* Primary text color*/
    color: #060606;
	display: inline-block;
	padding: 10px 35px;
	position: relative;
	font-size: 36px;
	line-height: 52px;
	/*margin-bottom: 40px;*/
	text-align: center;
	text-transform: none;
	letter-spacing: 1px !important;
}

 
h1:not(.site-title):not(.home_info_title) > span.h1_en, h1.entry-title:not(:first-child) > span.h1_en{
	font-weight: normal;
	display: block;
    font-size: 28px;
    line-height: 33px;
    color: #666666;
}


h2:not(.widget-title):not(.home_info_sub), h4.sponsor-level-title {
	/*color: #6b9bd2;
	font-size: 28px;*/
	/* Primary text color*/
	color: #060606;
    font-size: 28px;
    line-height: 42px;
    font-weight: 700;
}

h2:not(.widget-title):not(.home_info_sub):before, h4.sponsor-level-title:before {
	content: '';
	display: inline-block;
	width: 28px;
	height: 37px;
	background-image: url(http://wordcamptest.local/wp-content/themes/wctw2021/dest/img/wctpe-2021-icons-title.svg);
	background-size: contain;
	background-repeat: no-repeat;
	margin-right: 1em;
	vertical-align: -20%;
}

@media (min-width:0em) and (max-width:47.999em) {

	h1:not(.site-title):not(.home_info_title), h1.entry-title:not(:first-child), .page .panel-content .entry-title, .page-title, body.page:not(.twentyseventeen-front-page) .entry-title, .site-footer .widget-column.footer-widget-1 h2.widget-title {

		padding: 0px 0px;		
		font-size: 24px;
		line-height: 36px;
	}
	
	 
	h1:not(.site-title):not(.home_info_title) > span.h1_en, h1.entry-title:not(:first-child) > span.h1_en{
		font-weight: normal;
		display: block;
		font-size: 20px;
		line-height: 28px;
		color: #666666;
	}
	
	header.entry-header::before {
		padding: 0em 0.5em;
	}
	header.entry-header::after {
		padding: 0em 0.5em;

	}
	
	h2:not(.widget-title):not(.home_info_sub):before, h4.sponsor-level-title:before {
		margin-right: 0.5em;
	}

}	
/* end: Josh 2021 edited */





part2 ----
/*line 2070 ~ 2202 */

/*網站各個按鈕樣式*/
/*  Josh edited 2021 Sept */
.entry-content .wp-block-button__link {
	/*background-color: #1FAC43;
	color: #fff;
	border-radius: 5px;
	font-weight: 800;
	font-size: 14px;
	line-height: 1;
	margin-top: 20px;
	padding: .75em 2em;
	text-decoration: none;
	color: #ffffff;
	border-radius: 10px 10px 0 10px;
	-webkit-box-shadow: 0 0 10px 0 rgba(0,0,0,0.2);
	        box-shadow: 0 0 10px 0 rgba(0,0,0,0.2);
	background: -webkit-gradient(linear,left top, left bottom,from(145DEG),color-stop(#7BC16D),to(#20AB41));
	background: -o-linear-gradient(145DEG,#7BC16D,#20AB41);
	background: linear-gradient(145DEG,#7BC16D,#20AB41);
	-webkit-transition: all .2s ease-in-out;
	-o-transition: all .2s ease-in-out;
	transition: all .2s ease-in-out;*/
	background-color: #23459A;
    color: #fff;
    border-radius: 5px;
    font-weight: 800;
    font-size: 14px;
    line-height: 1em;
    margin-top: 20px;
    padding: .75em 2em;
    text-decoration: none;
    color: #ffffff;
    border-radius: 10px 10px 0 10px;
	background: -webkit-gradient(linear,left top, left bottom,from(145DEG),color-stop(#3160d4),to(#23459A));
	background: -o-linear-gradient(145DEG,#3160d4,#23459A);
    /*-webkit-transition: all .2s ease-in-out;
    -o-transition: all .2s ease-in-out;
    transition: all .2s ease-in-out;*/
    background: #23459A;
    border: 2px solid #060606;
    box-sizing: border-box;
    border-radius: 10px;
    font-weight: 500;
    font-size: 18px;
    padding: 0.7em 3.5em;
    margin: 1em 2em;
    filter: drop-shadow(0px 4px 0px #000000);
    
}

@media  (min-width:0em) and (max-width:47.999em)  {
	.entry-content .wp-block-button__link {
		padding: 1em 1.5em;
	}
}


/*網站單獨按鈕樣式*/
.entry-content .wp-block-button__link:hover, .entry-content .wp-block-button__link:focus, .entry-content .is-style-outline .wp-block-button__link:not(.has-background):hover, .entry-content .is-style-outline .wp-block-button__link:not(.has-background):focus {
	/* background-color: #23459A; */
	background: -webkit-gradient(linear,left top, left bottom,from(145DEG),color-stop(#3160d4),to(#23459A));
	background: -o-linear-gradient(145DEG,#3160d4,#23459A);
	background: linear-gradient(145DEG,#3160d4,#23459A);
	color: white;
	border: 2px solid #060606;
    box-sizing: border-box;
    border-radius: 10px;
	/*-webkit-box-shadow: 0 2px 10px 0 rgba(0,0,0,0.3);
	        box-shadow: 0 2px 10px 0 rgba(0,0,0,0.3);
	opacity: .9;
	-webkit-transform: scale(1.04);
	    -ms-transform: scale(1.04);
	        transform: scale(1.04);*/
}

a.wp-block-button__link:active {
	background-color: #23459A;
}


input[type="text"],
input[type="email"]:not(#subscribe-field-blog_subscription-4),
input[type="url"],
input[type="tel"],
textarea {
  border:  1px solid #060606 !important;
  border-radius: 10px;
  background: rgba(253, 215, 8, 0.1) !important;
}
input[type="text"]:focus,
input[type="email"]:not(#subscribe-field-blog_subscription-4):focus,
input[type="url"]:focus,
input[type="tel"]:focus,
textarea:focus {
	border:  1px solid #060606 !important;
}
select {
	border:  1px solid #060606 !important;
  border-radius: 10px;
  background: rgba(253, 215, 8, 0.1) !important;
}

p.contact-submit{
	text-align: center;
}
button:not([name="jetpack_subscriptions_widget"]):not(.menu-toggle):not(.dropdown-toggle), input[type="button"], input[type="submit"] {
    background: #FDD708;
    border: 2px solid #060606;
    box-sizing: border-box;
    border-radius: 10px;
    font-weight: 500;
    font-size: 18px;
    padding: 0.7em 3.5em;
    margin: 1em 2em;
    filter: drop-shadow(0px 4px 0px #000000);
}



button.dropdown-toggle {color:#ffffff;}
button:not([name="jetpack_subscriptions_widget"]):not(.menu-toggle):not(.dropdown-toggle):hover, input[type="button"]:hover, input[type="submit"]:hover {
	background: #FDD708;
    border: 2px solid #060606;
    box-sizing: border-box;
    border-radius: 10px;
    font-weight: 500;
    font-size: 18px;
    padding: 0.7em 3.5em;
    margin: 1em 2em;
    filter: drop-shadow(0px 4px 0px #000000);
}
button.dropdown-toggle:hover {/*color:#ffffff;*/}
/* end- Josh edtied 2021 Sept*/
