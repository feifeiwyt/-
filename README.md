# -
```
css格式化导航菜单
html部分
<body>
 <header>
 <div class="logo"></div>
  <nav>
  <ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
  <li>Jquery</li>
  <li>vueJs</li>
  <li>AngularJs</li>
  <li>More...</li>
  </ul>
  </nav>
 </header>
</body>
```
一个简单的列表。现在的样子打开就和在word上抠字一样，很low
加上css后
```
<html>
<head>
    <title>实验室导航菜单</title>
<style>
  ul{ 
    list-style:none;           <!--去掉表头的黑点-->
    display:inline-block;      <!--让ul变成行内块元素-->
    padding-left:0;
  } 
  li{
    display:inline-block;    <!--让li元素变成行内块元素-->
width:140px;
    text-align:center;     
    line-height:51px;       <!--让文字垂直水平居中-->
  } 
div.logo{
  width:160px;
  height:51px;
  background:url(logo.png);
  display:inline-block;
  margin-right:10%;       <!--使logo更加贴近窗口-->
  }  
  div.logo,ul{vertical-align: middle;}   <!--使logo和列表都居中排列-->
li:hover{
   color:white;
   background-color:#11278a;
   cursor:pointer;
   font-weight:bold;
}               <!--设置变色，鼠标选中后由白变蓝-->
 body,ul{
  margin:0;
 }          <!--格式化让导航更加贴近窗口-->
li:nth-child(1){
background-color:#11278a;
color:white;
font-weight:bold;
}              <!--li块中元素的格式-->

header{
height:55px;
padding-bottom:2px;
border-bottom:1px solid #e3e3e3;
}    
nav{
display:inline-block;
}
</style>
<body>
 <header>
  <div></div>
  <nav>
  <ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
  <li>Jquery</li>
  <li>vueJs</li>
  <li>AngularJs</li>
  <li>More...</li>
  </ul>
  </nav>
 </header>
</body>

</html>
</head>
</html>
```
效果就好看了很多
