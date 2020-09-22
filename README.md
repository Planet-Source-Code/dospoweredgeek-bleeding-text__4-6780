<div align="center">

## BLEEDING TEXT


</div>

### Description

This makes your page stand out. Brightens the page. You can place it where ever you need the text.
 
### More Info
 
I have clearly labeled where to edit and where not to.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[DOSpoweredGEEK](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/dospoweredgeek.md)
**Level**          |Advanced
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |HTML
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__4-1.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/dospoweredgeek-bleeding-text__4-6780/archive/master.zip)





### Source Code

```
<span id="theText" style="width:100%">
<h2>This is Pulsating Text!!</h2>
</span>
<script>
<!--
/*
Pulsating Text (Richard Smythe)
*/
//range of glowing
var from = 5;
var to = 11;
//speed of pulsing
var delay = 55;
//color of glow, name or RGB value (example:'#00FF00')
var glowColor = "lime";
//NO MORE EDITING!!!
var i = to;
var j = 0;
//can be called here or whenever you want the text to start pulsing
textPulseDown();
function textPulseUp()
{
if (!document.all)
return
if (i < to)
{
theText.style.filter = "Glow(Color=" + glowColor + ", Strength=" + i + ")";
i++;
theTimeout = setTimeout('textPulseUp()',delay);
return 0;
}
if (i = to)
{
theTimeout = setTimeout('textPulseDown()',delay);
return 0;
}
}
function textPulseDown()
{
if (!document.all)
return
if (i > from)
{
theText.style.filter = "Glow(Color=" + glowColor + ", Strength=" + i + ")";
i--;
theTimeout = setTimeout('textPulseDown()',delay);
return 0;
}
if (i = from)
{
theTimeout = setTimeout('textPulseUp()',delay);
return 0;
}
}
//-->
</script>
```

