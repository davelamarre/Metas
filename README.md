Metas Mobile and Such.
========


#### Repository of all proper meta tags ####

To put it simply, everytime if start a project i am looking for this, a proper package of all facebook and mobile related meta tags, favicons and splash screen resolution (retina or not). With all the proper width and height. If you find any errors in this, please tell me!

#### Make the URL and button bars disappear, ####
	
	<meta name="apple-mobile-web-app-capable" content="yes" /> 


#### Scale the viewport accordingly. ####

	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no" />


#### Other options ####

width – Width of viewport in pixels. [Default: 980, Range: 200 - 10,000]
height – Height of viewport in pixels. [Default: calculated with the width and aspect ratio of the device, Range: 223 - 10,000]
initial-scale – The initial scale of the viewport. [Default: calculated to fit the webpage in the area available, Range: calculated with minimum-scale and maximum-scale properties.]
minimum-scale – The minimum scale of viewport. [Default: 0.25, Range: >0 - 10]
maximum-scale – The maximum scale of viewport. [Default: 1.6, Range: >0 - 10]
user-scalable – Whether the user can zoom in and out. [Default: yes, Options: yes or no]
 
 - This info comes from : http://mobile.tutsplus.com/tutorials/iphone/iphone-web-app-meta-tags/


#### STATUS BAR ####
Change the status bar style (other content options includes : black / black-translucent / default
	
	<meta name="apple-mobile-web-app-status-bar-style" content="default" />  

#### FAV ICONS ####

	<link rel="icon" href="/images/icons/favicon.ico" type="image/x-icon">
	<link rel="icon" href="/images/icons/favicon_16px.png" sizes="16x16" type="image/png">
	<link rel="icon" href="/images/icons/favicon_32px.png" sizes="32x32" type="image/png">
	<link rel="shortcut icon" href="/images/icons/favicon.png">

#### BOOKMARK ICONS ####

	<link href="/images/icons/icon_57.png" sizes="57x57" rel="apple-touch-icon">
	<link href="/images/icons/icon_72.png" sizes="72x72" rel="apple-touch-icon">
	<link href="/images/icons/icon_114px.png" sizes="114x114" rel="apple-touch-icon">
	<link href="/images/icons/icon_144px.png" sizes="144x144" rel="apple-touch-icon">

#### STARTUP IMAGES LANDSCAPE / PORTRAIT ####
	This is the generic startup image, it will be used if none of the other start-up images are triggered threw their <media> parameters
	
	<link href="/images/icons/touch-icon-iphone-startup-320x460.png" media="(device-width: 320px) and (device-height: 480px) and (-webkit-device-pixel-ratio: 1)" rel="apple-touch-startup-image">

#### STARTUP IMAGES LANDSCAPE / PORTRAIT RETINA ####
	
	<link href="/images/icons/touch-icon-ipad-startup-768x1004.png" media="(device-width: 768px) and (device-height: 1024px) and (orientation: portrait) and (-webkit-device-pixel-ratio: 1)" rel="apple-touch-startup-image">
	<link href="/images/icons/touch-icon-ipad-startup-1024x748.png" media="(device-width: 768px) and (device-height: 1024px) and (orientation: landscape) and (-webkit-device-pixel-ratio: 1)" rel="apple-touch-startup-image">


	<link href="/images/icons/touch-icon-iphone-retina-startup-640x920.png" media="(device-width: 320px) and (device-height: 480px) and (-webkit-device-pixel-ratio: 2)" rel="apple-touch-startup-image">
	<link href="/images/icons/touch-icon-iphone-retina-startup-640x1096.png" media="(device-width: 320px) and (device-height: 568px) and (-webkit-device-pixel-ratio: 2)" rel="apple-touch-startup-image">

	<link href="/images/icons/touch-icon-ipad-retina-startup-1536x2008.png" media="(device-width: 768px) and (device-height: 1024px) and (orientation: portrait) and (-webkit-device-pixel-ratio: 2)" rel="apple-touch-startup-image">
	<link href="/images/icons/touch-icon-ipad-retina-startup-2048x1496.png" media="(device-width: 768px) and (device-height: 1024px) and (orientation: landscape) and (-webkit-device-pixel-ratio: 2)" rel="apple-touch-startup-image">


#### Android ####

	It is safe to assume that today all browsers for Android smartphones 
	support the viewport meta tag but that there are probably no other specific tags.

 
#### Facebook Open Graph Meta Tags ####

	<!-- Share Image -->

	<meta property="og:image" content="http://www.myimage.com/image.png"/>
	# Note that the width and height of this thing varies constantly. 
	# Its currently 200x200
	
	<!-- Title -->
	<meta property="og:title" content="Facebook Open Graph META Tags"/>

	<!-- Site URL -->
	<meta property="og:url" content="http://mywebsite.com"/>

	<!-- Site Name -->
	<meta property="og:site_name" content="My Website Name"/>

	<!-- Site Type -->
	<meta property="og:type" content="blog"/>

	<!-- Other : 
	 - Visit : https://developers.facebook.com/docs/concepts/opengraph/
	 For more information. Good luck! Facebook doc is a mess.
	-->

#### Identifying Mobile Websites ####
*Warning, these are deprecated tags to be used only when  the viewport tag doesnt cut it..


	<meta name="HandheldFriendly" content="true" />

	This will indentify your website as mobile friendly, however its range of supported browsers is unkkown


	<meta name="MobileOptimized" content="320">

	This will indentify your website as mobile friendly, however its range of supported browsers is unkkown









