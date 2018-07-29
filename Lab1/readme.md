1. button的自定义样式：单独写在一个xml文件中，存放到drawable文件夹中，<br>
在main.xml中，利用button的 android:background="@drawable/button_border" background属性添加进去（注意背景色要设置到xml里面）<br>
链接：https://blog.csdn.net/sysukehan/article/details/52022307
<br>
两个button要变成链条，相互链接（约束：A在B右面，B在A左面），还要两个button和parent的左面和右面链接,<br>
最后设置链条方式：        
   app:layout_constraintHorizontal_chainStyle="packed"
