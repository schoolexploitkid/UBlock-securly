uRun - Bypass bookmarklet restrictions with uBlock
Note: Google is deprecating mv2, so uBlock will not work as of Oct 24, and will be fully removed for enterprise as well in June 25. More info here
From Inglan2
Recently Google cracked down on bookmarklets and now they don't work (It's based on the DeveloperToolsAvailability policy). I wanted to run scripts still so I started making this, inspired by uBlock Run Run Code On Pages, but with more features, like saving scripts.
Open uBlock settings
Enable advanced settings, and click the gear ⚙️ button
Caution: DO NOT MODIFY ANYTHING ELSE ON THIS PAGE UNLESS YOU KNOW WHAT YOU ARE DOING (you probably don't), AS YOU COULD BREAK SOMETHING.
Tip: If you mess up, go to the home of settings and at the bottom click reset to default settings
Add the script
Change `userResourcesLocation unset` to `userResourcesLocation https://inglan2.github.io/uRun/urun.js`
Tip: It's down the bottom
Set a filter to load uRun
After closing the advanced settings tab, go to the filters tab and add this: `*##+js(urun.js)`
Usage: Simply press Ctrl + Shift + ` to open the menu and from there you can run and create scripts. To add a script, press the ➕ button up the top right, and enter the code you would like to add (without the javascript: part).
