<h2>uBlock Run Run Code On Pages</h2>
Note: Google is deprecating mv2, so uBlock will not work as of Oct 24, and will be fully removed for enterprise as well in June 25.<br>
If your school allows the uBlock Origin Chrome extension, you can run bookmarklets with the extension.<br>
Requirements:<br>
uBlock Origin<br>
Getting started<br>
Make sure you have uBlock Origin installed.<br>
Go to the extension's settings.<br>
Under the settings tab, check the "I am an advanced user" box, then click on the small cog icon.<br>
Find <code>userResourcesLocation</code> and change it from <code>unset</code> to <code>https://raw.githubusercontent.com/3kh0/ext-remover/main/ublockExec.js</code>.<br>
Go to the filters tab of the settings and add the following line:<br>
<code>*##+js(execute_script.js)</code><br>
Now press ctr+alt+tilde (~) to run code on the current page<br>
Have fun!<br>
