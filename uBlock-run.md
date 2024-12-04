uBlock Run Run Code On Pages<br>
Note: Google is deprecating mv2, so uBlock will not work as of Oct 24, and will be fully removed for enterprise as well in June 25.<br>
If your school allows the uBlock Origin Chrome extension, you can run bookmarklets with the extension.<br>
Requirements:<br>
uBlock Origin<br>
Getting started<br>
Make sure you have uBlock Origin installed.<br>
Go to the extension's settings.<br>
Under the settings tab, check the "I am an advanced user" box, then click on the small cog icon.<br>
Find `userResourcesLocation` and change it from `unset` to `https://raw.githubusercontent.com/3kh0/ext-remover/main/ublockExec.js`.<br>
Go to the filters tab of the settings and add the following line:<br>
`*##+js(execute_script.js)`<br>
Now press ctr+alt+tilde (~) to run code on the current page<br>
Have fun!<br>
