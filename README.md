<h1 align="center">firefox-bottom-ui</h1>

<p align="center"><img src="https://user-images.githubusercontent.com/7110136/121684904-fef98480-cac7-11eb-9065-86f09af823cb.png"></img></p1>
<p align="center"><img src="https://user-images.githubusercontent.com/7110136/121684891-fb65fd80-cac7-11eb-847a-aeaedbd7a4e3.png"></img></p1>
<!-- <p align="center"><img src="https://user-images.githubusercontent.com/7110136/90187878-34a7e100-ddc3-11ea-89c7-8d492c43718b.gif"></img></p1> -->

### Steps for applying this configuration
* Type `about:profiles` into your urlbar and go to the page
* Open the root directory folder specified on the page
* Inside this folder, create a folder named `chrome`
* Put the `userChrome.css` file from this repo into the chrome folder
* Type `about:config` into your urlbar and go to the page
* Paste `toolkit.legacyUserProfileCustomizations.stylesheets` into the bar and set its value to `true`
* Go back to `about:profiles` and click the restart normally buton
* That should be it!
