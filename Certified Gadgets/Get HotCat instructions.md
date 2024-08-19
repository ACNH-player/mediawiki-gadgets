# HotCat
## About HotCat
HotCat is a popular mediawiki gadget used to quickly add and remove categories from pages. It is a semi-automated tool used on wikimedia projects including wikipedia.
## Get HotCat
Here are the instructions on how to get HotCat for your wiki: <br>
**If you do not have the "gadget" extension yet:** Download the "Gadgets" extension from mediawiki [on this page](https://www.mediawiki.org/wiki/Extension:Gadgets), you can get instructions on that page. You *must* have the gadgets extension for this to work.<br>
<br>
1. Go to the page "MediaWiki:Gadgets-definition" and add the following text: ```HotCat[ResourceLoader]|HotCat.js``` and save the page.
2. Create the page "MediaWiki:Gadget-HotCat" and write a simple discription for your gadget; this will be what users will see on the checkboxes to enable the gadget. (Example: ```HotCat: Quickly add and remove categories from pages using a semi-automated tool```)
3. Create the page "MediaWiki:Gadget-HotCat.js" and insert the following code:<br>```window.hotcat_translations_from_commons = true;
mw.loader.load( '//commons.wikimedia.org/w/index.php?title=MediaWiki:Gadget-HotCat.js&action=raw&ctype=text/javascript' );```
4. Go to your preference page and go to the "gadgets" section. Try enabling the gadget. You can look at the instructions on how to use the gadget in another file in this file folder.
