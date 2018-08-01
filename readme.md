## appened to /Applications/Slack.app/Contents/Resources/app.asar.unpacked/src/static/ssb-interop.js

document.addEventListener('DOMContentLoaded', function() {
 $.ajax({
   url: '**URL GOES HERE**',
   success: function(css) {
     $("<style></style>").appendTo('head').html(css);
   }
 });
});
