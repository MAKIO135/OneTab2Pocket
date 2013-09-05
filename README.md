OneTab2Pocket
=============

Bookmarklet sending [OneTab](http://www.one-tab.com/) links to [Pocket](http://getpocket.com/).

#Notes#
Make sure you're logged into Pocket before using.
It seems Chrome doesn't allow using bookmarklet on extensions tabs so:<br>
__Once you've used OneTab, click on the "Share all as web page" link (top right of the tab created by the extension) and on the "http://www.one-tab.com/page/..." use the bookmarklet.__

To install the bookmarklet select the following line of code, drag'n drop it to your favorites and rename it "OneTab2Pocket":
 ```javascript
javascript:void((function(){var e=document.createElement('script');e.setAttribute('type','text/javascript');e.setAttribute('src','http://ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js');document.body.appendChild(e);var f=document.createElement('script');f.setAttribute('type','text/javascript');f.setAttribute('src','https://raw.github.com/MAKIO135/OneTab2Pocket/master/oneTab2Pocket.js');document.body.appendChild(f)})())
 ```

