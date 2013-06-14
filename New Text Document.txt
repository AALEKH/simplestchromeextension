var first=prompt("give value","");
var third=prompt("enter the operation you want to make","");
if(third==="add")
{
var second=prompt("give second value","");
var forth=Number(first)+Number(second);
document.writeln("<p>");
document.writeln(forth);
document.writeln("</p>");
}
else if(third==="subs")
{
var second=prompt("give second value","");
var forth=Number(first)-Number(second);
document.writeln("<p>");
document.writeln(forth);
document.writeln("</p>");
}
else if(third==="mult")
{
var second=prompt("give second value","");
var forth=Number(first)*Number(second);
document.writeln("<p>");
document.writeln(forth);
document.writeln("</p>");
}
else if(third==="div")
{
var second=prompt("give second value","");
var forth=Number(first)/Number(second);
document.writeln("<p>");
document.writeln(forth);
document.writeln("</p>");
}
else if(third==="cos")
{
first=Number(first);
var forth=Math.cos(first);
document.writeln("<p>");
document.writeln(forth);
document.writeln("</p>");
}
else if(third==="sin")
{
first=Number(first);
var forth=Math.sin(first);
document.writeln("<p>");
document.writeln(forth);
document.writeln("</p>");
}
else if(third==="tan")
{
first=Number(first);
var forth=Math.tan(first);
document.writeln("<p>");
document.writeln(forth);
document.writeln("</p>");
}
else if(third==="sec")
{
first=Number(first);
var forth=Math.cos(first);
forth=1/forth;
document.writeln("<p>");
document.writeln(forth);
document.writeln("</p>");
}
else if(third==="cosec")
{
first=Number(first);
var forth=Math.sin(first);
forth=1/forth;
document.writeln("<p>");
document.writeln(forth);
document.writeln("</p>");
}
else if(third==="cot")
{
first=Number(first);
var forth=Math.tan(first);
forth=1/forth;
document.writeln("<p>");
document.writeln(forth);
document.writeln("</p>");
}
else{
document.writeln("<p>");
document.writeln("wrong option");
document.writeln("</p>");
}
