# facebook-share-d4u
Share a facebook page from your website.

Reference: https://developers.facebook.com/docs/plugins/share-button/

Jvascript SDK Method: 
In the facebook developers dashboard make an app amke it public and make a note of the App ID and language.


Include the JavaScript SDK on your page once right after the opening body tag.

<div id="fb-root"></div>
<script async defer crossorigin="anonymous" src="https://connect.facebook.net/en_GB/sdk.js#xfbml=1&version=v9.0&appId=1318383554971490&autoLogAppEvents=1" nonce="9ObzPSix"></script>


Place the code where you want the share button to appear on your webpage.

<div class="fb-share-button" data-href="https://www.facebook.com/profile.php?id=100008770982035" data-layout="button" data-size="large"><a target="_blank" href="https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D100008770982035&amp;src=sdkpreparse" class="fb-xfbml-parse-ignore">Share</a></div>

