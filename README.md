<div align="center">

## Manipulating scrollbar colors using CSS and JavaScript\!


</div>

### Description

The thing about the default color of scrollbars is that it's dull and ugly. Wouldn't it be nice to change this color to better fit the overall theme of your site? See how to use Cascading Style sheets and JavaScript to do just that!
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Ada Shimar](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/ada-shimar.md)
**Level**          |Beginner
**User Rating**    |4.7 (14 globes from 3 users)
**Compatibility**  |
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__2-68.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/ada-shimar-manipulating-scrollbar-colors-using-css-and-javascript__2-2394/archive/master.zip)





### Source Code

<html>
<head>
<title>Manipulating scrollbar colors using CSS and JavaScript</title>
<style>
<!--
BODY{
scrollbar-face-color:#8080FF;
scrollbar-arrow-color:#FFFFFF;
scrollbar-track-color:#DDDDFF;
scrollbar-shadow-color:'';
scrollbar-highlight-color:'';
scrollbar-3dlight-color:'';
scrollbar-darkshadow-Color:'';
}
-->
</style>
</head>
<body>
<p><b><font size="4">Manipulating scrollbar colors using CSS and JavaScript!</font></b></p>
<p>The thing about the default color of scrollbars is that it's dull and ugly.
Usually this color is gray. Wouldn't it be nice to change this color to better
fit the overall theme of your site? Luckily Cascading Style sheets and
JavaScript can be used to do just that!</p>
<p><b>Using CSS</b></p>
<p>In CSS, you would just add this code to the top of your page to customize the browser's
scrollbar colors: The great thing about CSS is that browsers that don't
understand it will just skip it, in this case, Netscape browsers.</p>
<p><font size="3" face="Courier" color="#008000">&lt;style><br>
&lt;!--<br>
BODY{<br>
scrollbar-face-color:#8080FF;<br>
scrollbar-arrow-color:#FFFFFF;<br>
scrollbar-track-color:#DDDDFF;<br>
scrollbar-shadow-color:'';<br>
scrollbar-highlight-color:'';<br>
scrollbar-3dlight-color:'';<br>
scrollbar-darkshadow-Color:'';<br>
}<br>
--><br>
&lt;/style></font></p>
<p>Play around with the different values!</p>
<p><b>Using JavaScript</b></p>
<p>I can use JavaScript to dynamically change the scrollbar color. This is
useful when I wish to do something more fancy, like alternating the scrollbar
from one color to another. The code required is:</p>
<p><font size="3" face="Courier" color="#008000">document.body.style.scrollbarFaceColor=&quot;colorname&quot;<br>
document.body.style.scrollbarArrowColor=&quot;colorname&quot;<br>
document.body.style.scrollbarTrackColor=&quot;colorname&quot;<br>
document.body.style.scrollbarShadowColor=&quot;colorname&quot;<br>
document.body.style.scrollbarHighlightColor=&quot;colorname&quot;<br>
document.body.style.scrollbar3dlightColor=&quot;colorname&quot;<br>
document.body.style.scrollbarDarkshadowColor=&quot;colorname&quot;</font></p>
<p>A very good demonstration of this is a script written by Svetlin Staev, which
changes the scrollbar colors when you move your mouse over and out of it: <a href="http://www.dynamicdrive.com/dynamicindex11/scrolleffect.htm"><b>http://www.dynamicdrive.com/dynamicindex11/scrolleffect.htm</b></a></p>
<p>I'm seeing more and more sites customize the scrollbar color to blend in with
the rest of their sites. Hope ya find this tutorial useful in helping you do the
same!</p>
</body>
</html>

