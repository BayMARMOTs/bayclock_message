# bayclock_message
embed with `<iframe src="https://baymarmots.github.io/bayclock_message"></iframe>`

changes to main site:
`<body style="margins: 0; padding: 0;position:absolute; top:0px; left:0px; bottom:0px; right:0px; width:100%; height:100%; border:none; margin:0; padding:0; overflow:hidden; z-index:999999;">
<iframe style="position:absolute; top:0px; left:0px; bottom:50%; right:0px; width:100%; height:100%; border:none; padding:0; z-index:999999;" id="clock" src="clock.html">
</iframe>
	<iframe style="position:absolute;width:100%; top:50%;left:0px;right:0px;bottom:0px;border:none;padding:0;overflow:hidden;" src="https://baymarmots.github.io/bayclock_message/"></iframe>
<script>
setInterval(function() {
	document.getElementById("clock").src="clock.html";
	document.getElementById("clock").contentWindow.location.reload(true);
}, 1000*60*60); // Refresh every hour, in case javascript update daemon dies for some reason
</script>


</body>`
