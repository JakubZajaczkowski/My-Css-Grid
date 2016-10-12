# My First Grid
1-4 Columns. No javascript only Css. Easy Edit and Use.

###Setup Grid
1. Add css style your page:
  `<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
  <!-- Make the web page appear 100% instead of scaling -->
   <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0;" />	
	<!-- 1024px -->
	<link href="jz-1024.css" type="text/css" rel="stylesheet" media="only screen and (min-width: 1024px)">
	<!-- 768px -->
	<link href="jz-768.css" type="text/css" rel="stylesheet" media="only screen and (min-width: 768px) and (max-width: 1023px)">
	<!-- 480px -->
	<link href="jz-480.css" type="text/css" rel="stylesheet" media="only screen and (min-width: 480px) and (max-width: 767px)">
	<!-- 320 -->
	<link href="jz-320.css" type="text/css" rel="stylesheet" media="only screen and (min-width: 0px) and (max-width: 479px)">
	<!--  cols -->	
   <link href="jz-padding.css"	type="text/css" rel="stylesheet" media="only screen and (min-width: 0px)">`

2. Add your first colmun:
`<div class="col2">
	<div class="jz-1">
		1 col
	</div>
	<div class="jz-2">
		2 col
	</div>
</div>`

### Current Version : v1.0

## Supported Browsers:
Chrome 35+, Firefox 31+, Safari 7+, IE 10+

## Changelog
- v1.0 (Oct 12rd)
  - add 1-4 columns