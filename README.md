# JavaScript
I'm a beginner.
1.if...else...
if (time<20) {     x="Good day"; } 
else {     x="Good evening"; }
if (time<10) {     document.write("<b>早上好</b>"); } 
else if (time>=10 && time<16) {     document.write("<b>今天好</b>"); } 
else {     document.write("<b>晚上好!</b>"); }
2.switch
var d=new Date().getDay(); 
switch (d) 
{ 
  case 0:x="今天是星期日"; 
  break; 
  case 1:x="今天是星期一"; 
  break; 
  case 2:x="今天是星期二"; 
  break; 
  case 3:x="今天是星期三"; 
  break; 
  case 4:x="今天是星期四"; 
  break; 
  case 5:x="今天是星期五"; 
  break; 
  case 6:x="今天是星期六"; 
  break; 
}
3.break&continue
for (i=0;i<10;i++)
{
    if (i==3)
    {
        break;
    }
    x=x + "The number is " + i + "<br>";
}
for (i=0;i<=10;i++)
{
    if (i==3) continue;
    x=x + "The number is " + i + "<br>";
}
4.typeof, null 和 undefined
typeof来检测变量的数据类型
null来表示一个空对象引用，或者可以用来清空对象
undefined可以用来清空对象
