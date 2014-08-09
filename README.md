jsCookies 2.0
=========

Easily create cookies with JavaScript without having to make a custom cookies script.


Usage
=========

Simply put this in the &lt;head&gt; of your code:

&lt;script type="text/javascript" src="../jscookies.js"&gt;&lt;/script&gt;

Get Cookie Value
=========
getCookie("name");

Create Cookie & Set Value
=========
setCookie("name","value",365);

<b>name</b> - Name of the cookie
<br/>
<b>value</b> - Value of the cookie
<br/>
<b>365</b> - Number of days till cookie expires

Delete Cookie
=========
eraseCookie("name");
