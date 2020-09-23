<div align="center">

## Dynamic Character Counter and Status Bar


</div>

### Description

I found this code in use on zeal.com and it was unique so I thought I'd post it here. This Javascript allows the user to type characters in a box and shows the percent complete of their allowable max number of characters as a dynamically changing status bar!
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Ian Ippolito \(vWorker\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/ian-ippolito-vworker.md)
**Level**          |Intermediate
**User Rating**    |4.0 (16 globes from 4 users)
**Compatibility**  |
**Category**       |[Controls/ Forms/ Graphics/ Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/controls-forms-graphics-menus__2-59.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/ian-ippolito-vworker-dynamic-character-counter-and-status-bar__2-1899/archive/master.zip)





### Source Code

```
<table cellpadding="3" cellspacing="0" width="600" align="center" border="0" bgcolor="#EEEEEE">
<tr>
<td align="right" valign="middle" height="2" width="30%" bgcolor="#EEEEEE"><b><font face="MS Sans Serif, Geneva, Arial, Helvetica" size="2">URL:</font></b></td>
<td align="left" valign="middle" height="2" width="70%" colspan="3" bgcolor="#EEEEEE"><input type="text" size="50" maxlength="500" value="http://www.planet-source-code.com/" name="/zeal/directory/EditWebsiteFormHandler.websiteEdit.url"><input type="hidden" name="_D:/zeal/directory/EditWebsiteFormHandler.websiteEdit.url" value=" "></td>
</tr>
<tr>
<td align="right" valign="middle" width="30%" bgcolor="#EEEEEE"><font face="MS Sans Serif, Geneva, Arial, Helvetica" size="2"><b>Title:</b></font></td>
<td align="left" valign="middle" width="70%" colspan="3" bgcolor="#EEEEEE"><input type="text" size="50" maxlength="255" value="Planet Source Code" name="/zeal/directory/EditWebsiteFormHandler.websiteEdit.title"><input type="hidden" name="_D:/zeal/directory/EditWebsiteFormHandler.websiteEdit.title" value=" "></td>
</tr>
<tr>
<td align="right" valign="top" width="30%" bgcolor="#EEEEEE"><font face="MS Sans Serif, Geneva, Arial, Helvetica" size="2"><b>Slogan:</b></font><br><font face="MS Sans Serif, Geneva, Arial, Helvetica" size="1">(No more than 500 characters)</font></td>
<td align="left" valign="middle" width="70%" colspan="3" bgcolor="#EEEEEE"><textarea cols="43" rows="2" onKeyUp=f1(this) onKeyDown=f1(this) onFocus=f1(this) onChange=f1(this) name="/zeal/directory/EditWebsiteFormHandler.websiteEdit.slogan"></textarea><input type="hidden" name="_D:/zeal/directory/EditWebsiteFormHandler.websiteEdit.slogan" value=" "></td>
</tr>
<script language="JavaScript1.1">
<!--
function f1(a){
x = 500 - a.value.length;
if (x < 0) { a.value = a.value.substring(0,500); x = 0; }
document.u1.width=350*(500-x)/500;
document.u1.alt=500-x+" chars used";
document.u2.width=350*x/500;
document.u2.alt=x+" chars available";
}
if ((navigator.appName.indexOf("Microsoft") != -1) && (parseInt(navigator.appVersion) >= 4)) {
document.write('<tr><td align="right" width="30%" bgcolor="#EEEEEE">&nbsp;</td><td align="left" width="70%" bgcolor="#EEEEEE" colspan="3">');
document.write('<table cellpadding="0" cellspacing="0" border="0" width="350">');
document.write('<tr>');
document.write('<td bgcolor="#0000ff" width="0"><img src="/images/trans.gif" name="u1" height="5" width="0"></td>');
document.write('<td bgcolor="#cccccc" width="350"><img src="/images/trans.gif" name="u2" height="5" width="350"></td>');
document.write('</tr>');
document.write('</table>');
document.write('</td></tr>');
}
else {
document.write(' ');
}
//--></script>
</table>
```

