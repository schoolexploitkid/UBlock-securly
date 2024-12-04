uBlock Run Run Code On Pages
Note

Google is deprecating mv2, so uBlock will not work as of Oct 24, and will be fully removed for enterprise as well in June 25. More info here

If your school allows the uBlock Origin Chrome extension, you can run bookmarklets with the extension.

Requirements
uBlock Origin
Getting started
Make sure you have uBlock Origin installed.
Go to the extension's settings.
Under the settings tab, check the "I am an advanced user" box, then click on the small cog icon.
Find userResourcesLocation and change it from unset to https://raw.githubusercontent.com/3kh0/ext-remover/main/ublockExec.js.
Go to the filters tab of the settings and add the following line:
*##+js(execute_script.js)
Now press ctr+alt+tilde (~) to run code on the current page
Have fun!
