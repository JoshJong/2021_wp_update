# 2021_wp_update

![alt text](https://github.com/JoshJong/2021_wp_update/blob/main/001-volunteer.png)

![alt text](https://github.com/JoshJong/2021_wp_update/blob/main/cms.png)

Update:
H1 font style / H1 Before After / H2 font style / H2 Before /Global linehight@min-width: 48em

@cms:
<span class="h1_container"><span class="h1_zhtw">志工招募</span><span class="h1_en">Call for Volunteers</span></span>


@css:
/* css line 49 */
/* Josh 2021 edited */
h1:not(.site-title):not(.home_info_title), h1.entry-title:not(:first-child), .page .panel-content .entry-title, .page-title, body.page:not(.twentyseventeen-front-page) .entry-title, .site-footer .widget-column.footer-widget-1 h2.widget-title {
	/*background-color: #0068b6;*/
	/* Primary text color*/
    color: #060606;
	display: inline-block;
	padding: 10px 35px;
	border-radius: 10px;
	position: relative;
	font-size: 36px;
	line-height: 52px;
	margin-bottom: 40px;
	text-align: center;
	text-transform: none;
	letter-spacing: 1px !important;
}

h1:not(.site-title):not(.home_info_title) > span.h1_container{
	display:inline-block;
}
h1:not(.site-title):not(.home_info_title) > span.h1_container >  span.h1_en, h1.entry-title:not(:first-child) > span.h1_container >   span.h1_en{
	font-weight: normal;
	display: block;
    font-size: 28px;
    line-height: 33px;
    color: #666666;
}

h1:not(.site-title):not(.home_info_title)::before /*, .site-footer .widget-column.footer-widget-1 h2.widget-title:before*/ {
	content: url(http://wordcamptest.local/wp-content/themes/wctw2021/wctw2021/dest/img/h1-before.svg);
    display: inline-block;
	/*position: absolute;*/
	top: 0;
    height: auto;
    padding: 0em 1.8em;
}
h1:not(.site-title):not(.home_info_title):after /*, .site-footer .widget-column.footer-widget-1 h2.widget-title:before*/ {
	content: url(http://wordcamptest.local/wp-content/themes/wctw2021/wctw2021/dest/img/h1-after.svg);
    display: inline-block;
	/*position: absolute;*/
	top: 0;
    height: auto;
    padding: 0em 1.8em;
	/*width: 0;
	height: 0;
	border-style: solid;
	border-width: 25px 0 25px 20px;
	border-color: transparent transparent transparent #0067b6;
	position: absolute;
	right: 15px;
	bottom: -20px;
	-webkit-transform: rotate(15deg);
	    -ms-transform: rotate(15deg);
	        transform: rotate(15deg);*/
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
	background-image: url(http://wordcamptest.local/wp-content/themes/wctw2021/wctw2021/dest/img/wctpe-2021-icons-title.svg);
	background-size: contain;
	background-repeat: no-repeat;
	margin-right: 10px;
	vertical-align: -20%;
}
/* end: Josh 2021 edited */



/* css line 177 */
@media screen and (min-width:48em) {

		/* Typography */
	    /* Josh 2021 edited */
		body,
		button,
		input,
		select,
		textarea {
			/*font-size: 16px;
			font-size: 1rem;*/
			line-height: 1.8;
		}
		/* end-Josh 2021 edited */
}


