---
layout: page
title: Where am I?
permalink: /whereami/
---

<div id="widget"></div>

<!--Google Maps v3 API -->
<script type="text/javascript" src="https://maps.googleapis.com/maps/api/js?key=AIzaSyDycs5UAKebcWcT9UZzKcxrfnqzu84ygwg"></script>
<!-- jQuery, Note: Do not include this line if jQuery is already present -->
<script type="text/javascript" src="//ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script> 
<script type="text/javascript" src="//d3ra5e5xmvzawh.cloudfront.net/live-widget/2.0/spot-main-min.js"></script>

<script type="text/javascript">
	$(function() {
		$('#widget').spotLiveWidget({ 
			feedId: '0BbHkTrRsS3Dj46lIpeNSm0yriMQguWz0',
			mapType: 'ROADMAP',
			width: 800,
			height: 500,
      			showLegend: false,
			autoRefresh: 10
		});
	});
</script>

_This page auto-refreshes every 10 minutes or so._
