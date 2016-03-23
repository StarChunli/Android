## Android:这个文件夹主要用来存放平时上课中的Android项目实例和自己开发的应用！
1、WeightNew：这个Android工程主要实现的是对男女体重计算功能！  
2、android-web：一个类似浏览器的应用软件，可以加载网页  
3、布局：  
（1）LinearLayout（线性布局）：按照垂直或水平的方向布局的组件。  
通过“android:orientation”属性可以设置线性布局的方向。属性值有垂直（vertical）和水平（horizontal）两种。  
常用的属性：  
android:orientation：可以设置布局的方向  
android:gravity:用来控制组件的对齐方式  
layout_weight：控制各个组件在布局中的相对大小    
（2）RelativeLayout（相对布局）：相对其他组件的布局方式。   
相对布局是按照组件之间的相对位置来布局，比如在某个组件的左边，右边，上面和下面等。
（3）tablelayout（表格布局）：相对行列方式布局组件。   
表格布局是一个ViewGroup以表格显示它的子视图（view）元素，即行和列标识一个视图的位置。  
表格布局常用的属性如下：  
android:collapseColumns：隐藏指定的列  
android:shrinkColumns：收缩指定的列以适合屏幕，不会挤出屏幕  
android:stretchColumns：尽量把指定的列填充空白部分  
android:layout_column:控件放在指定的列  
android:layout_span:该控件所跨越的列数
（4）FrameLayout（单帧布局）：组件从屏幕上方布局组件。  
帧布局是从屏幕的左上角（0,0）坐标开始布局，多个组件层叠排列，第一个添加的组件放到最底层，最后添加到框架中的视图显示在最上面。上一层的会覆盖下一层的控件。
（5）AbsoluteLayout(绝对布局)：按照绝对坐标来布局组件。  
 绝对布局通过指定子组件的确切X,Y坐标来确定组件的位置，在Android2.0 API文档中标明该类已经过期，可以使用FrameLayout或者RelativeLayout来代替。所以就没有相应的应用实例进行演示。
