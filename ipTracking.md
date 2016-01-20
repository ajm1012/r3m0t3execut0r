1)Create Account

2)Get one of the links and tell to click it, choose any of the images and tell them you painted it or some stupid shit like that.

3)When they look at the image, it logs their IP.

http://www.chatrack.frihost.net/index-1.php


http://www.whatstheirip.com


http://www.safeprofile.com


Script :
<?php
header('Content-type: image/jpeg');
readfile('image.jpg');
$logfile= 'thlog.html';
$IP = $_SERVER['REMOTE\_ADDR'];
$logdetails=  date("F j, Y, g:i a") . ': ' . '<a href=(placewhois lookup domain here)='.$_SERVER['REMOTE\_ADDR'].'>'.$_SERVER['REMOTE\_ADDR'].'

Unknown end tag for &lt;/a&gt;

';
$fp = fopen($logfile, "a");
fwrite($fp, $logdetails);
fwrite($fp, "_<br>");<br>
fclose($fp);<br>
?><br>
<br>
<br>
or<br>
<?php<br>
header('Content-type: image/jpeg');<br>
readfile('image.jpg');<br>
$filename = "logged.txt";<br>
<blockquote>$somecontent = "Connection from:".$<i>SERVER['REMOTE_ADDR']." at ".date("r",time())."\n";<br>
if ($handle = fopen($filename, 'a')) {<br>
<blockquote>fwrite($handle, $somecontent);<br>
fclose($handle);<br>
</blockquote>}<br>
?></blockquote></i>


Another Ways :<br>
<br>
1) Download Net Tools (Google)<br>
<br>
2)Start -> NetWork Tools -> Port Identfication List + IP thief etc (U Need To Go Down) -> Options -> IP- thief<br>
<br>
3)Now go on any url shortening service and paste your ip there thats done.Now tell anyone to go on that page and in IP-Thief you will get his IP.<br>
<br>
Note : If the Software is set to offline or is closed this trick will not work.<br>
<br>
Enjoy !