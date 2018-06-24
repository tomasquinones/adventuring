---
layout: default
title: Countdown
permalink: /countdown/
---
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"></script>
<script type="text/javascript" src="/path/to/jquery.countdown.js"></script>

$(function() {
    $('.yourCountdownContainer').countdown({
        date: "December 13, 2018 15:03:26"
    });
});
