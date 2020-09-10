***html表单中<input>属性id和name的区别***

**https://www.jianshu.com/p/7a171f96c1e0**

https://blog.csdn.net/qq_35038153/article/details/70215356

name:规定input元素的名称，姓名

id:规定html元素的唯一id，身份证



> **在表单接收页面里只能接收到name属性值;
>  ID只是在当页里控件的唯一标识(不可重复);**
>
>  **用到name的控件有  form  input  select  textarea  iframe  frame 
>
>  其它的元素都用不着  name  
>  ==========================================================   
>
>  name是对象的名字,id是标识,用以唯一性的区分.就象人既要有名字,又需要身份证号.  
>  可以这么简单理解它们的使用区别:id用于DHTML,即客户端脚本。而name则通常用在服务器端,例如Request.for("")中就要用name。 
>  你用<input  name=myinput  id=myinput>中,在客户端  
>
>  <script>  
>  alert(myinput.value)//这里是id  
>  </scipt> 

>  而提交后，用Request.form("myinput")，这里就是name。