# ========SOME TABS EXAMPLE=====
## 1. [Fixed Tabs](https://github.com/trantronghien/Tabs_host/tree/master/FixedTabs)
###* Simple Tabs </br>
![simpletabs](https://cloud.githubusercontent.com/assets/13708331/16866422/06c16fdc-4a96-11e6-8802-590e35aff1ff.png)
###* Full Width Tabs </br>
![fulltabs](https://cloud.githubusercontent.com/assets/13708331/16866458/408a7e98-4a96-11e6-9a96-2ff9ff7ca75b.png) </br>
 + với 1 số thuộc tính thay đổi phần  app:tabGravity=”fill” </br>

`<android.support.design.widget.TabLayout
            android:id="@+id/tabs"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            app:tabMode="fixed" 
            app:tabGravity="fill"/>` </br>
            
###* Center Aligned Tabs </br>
![centertabs](https://cloud.githubusercontent.com/assets/13708331/16866712/af89bae2-4a97-11e6-92fa-ba5e5d5eaa0f.png)
> thay đổi phần app:tabGravity=”center” 
## 2. Scrollable Tabs </br>
* với Scrollable Tabs tab ta xét thuộc tính </br>
` app:tabMode=”scrollable” ` </br>
![sroll](https://cloud.githubusercontent.com/assets/13708331/16866823/72f3478c-4a98-11e6-9fb4-4b07d6517af3.png) </br>

> sử dụng giống tabs thông thường nhưng vì nhu cầu cần nhiều tabs màn kích cỡ màn hình không cho phép nên ta dùng srollable tabs

