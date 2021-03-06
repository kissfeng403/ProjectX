# Drawable
![ICON](https://raw.githubusercontent.com/AlexMofer/ProjectX/master/drawable/icon.png)

实现特定功能的Drawable合集。
## 要求
minSdkVersion 4
## 引用
```
dependencies {
    ⋯
    compile 'am.drawable:drawable:1.4.0'
    ⋯
}
```
## 详情
- **DoubleCircleDrawable**

    双圈动图，用于载入提示。
- **CirclingDrawable**

    外围小点转圈动图。
- **CenterDrawable**

    中心图片，背景可绘制形状，一般用于ImageView的src，保证缩放后，中心的Drawable不变形。用于一般background属性的话，无需使用本控件，直接使用layer-list来定义即可。
- **CombinationDrawable**

    双层图片，与CenterDrawable类似，背景为另一Drawable，一般用于ImageView的src，保证缩放后，中心的Drawable不变形。用于一般background属性的话，无需使用本控件，直接使用layer-list来定义即可。
- **LineDrawable**

    横线图片，主要是底色为透明或半透明色时有用，为不透明时，通过layer-list即可实现。
- **LinearDrawable**
    
    线性图片，多张图片排列，支持设置间隔，主要用于替代多个ImageView排列，节省性能。
- **CornerDrawable**
    
    尖角框，使用该Drawable时，会改变View的Padding值。
- **TextDrawable**
    
    文字图片。
- **CircleExpandDrawable**
    
    圆圈扩大图片。
- **MaterialProgressDrawable**

    SwipeRefreshLayout载入动图。

## 历史
- [**1.3.0**](https://bintray.com/alexmofer/maven/Drawable/1.3.0)
- [**1.2.2**](https://bintray.com/alexmofer/maven/Drawable/1.2.2)
- [**1.2.1**](https://bintray.com/alexmofer/maven/Drawable/1.2.1)
- [**1.2.0**](https://bintray.com/alexmofer/maven/Drawable/1.2.0)
- [**1.1.0**](https://bintray.com/alexmofer/maven/Drawable/1.1.0)
- [**1.0.1**](https://bintray.com/alexmofer/maven/Drawable/1.0.1)
- [**1.0.0**](https://bintray.com/alexmofer/maven/Drawable/1.0.0)