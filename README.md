# chrome-ex-gun-test

Chrome Extension using GunDb to add the last clicked URL (of any user of this extension) to the list of type urls of other users of the extension. Kinda silly but wanted to show Gun in Chrome Extension without using any browswer storage permissions. 

Based on Tyed History example from Chrome devs.

https://developer.chrome.com/extensions/samples#search:history

This is currently using a Gun 'super' peer called 
https:/kmm-gun.herokuapp.com on Heroku free tier so the data wont be saved forever. Good enough for demos.

See typedUrls.js for the gun.get.put/on calls.