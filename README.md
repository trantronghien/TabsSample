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

## 3. Tabs with Icon & Text </br>
* [Icon & Text](https://github.com/trantronghien/Tabs_host/tree/master/Tabs_Icon) </br>
 ![icontext](https://cloud.githubusercontent.com/assets/13708331/16893072/7a2d076e-4b55-11e6-9dba-1845c1154c0b.png)
* [Icon Only](https://github.com/trantronghien/Tabs_host/tree/master/Tabs_Icon) </br>
 ![onlyicon](https://cloud.githubusercontent.com/assets/13708331/16893076/87ad2c34-4b55-11e6-80fe-97b8cd1b88f2.png)
* [Custom Tabs](https://github.com/trantronghien/Tabs_host/tree/master/Custom_tabs) </br>
![customviewicontext](https://cloud.githubusercontent.com/assets/13708331/16893077/8fff25fe-4b55-11e6-93cb-600a93813086.png)

* ### Một Số Chú Ý </br>
![loi_style](https://cloud.githubusercontent.com/assets/13708331/16894480/a2f65106-4b81-11e6-9995-a58e1e9671e8.png)
+ thêm  2 item này vào style nếu thiếu sẽ gặp lỗi như trên </br>
        `<item name="windowNoTitle">true</item>
        <item name="windowActionBar">false</item>`
+ add Thư Viện hỗ trợ 'com.android.support:design:23.0.1;' nếu sử dụng các mẫu tabs này </br>
thêm phần compile 'com.android.support:design:23.0.1' vào dependencies trong gradle '23.0.1' tùy theo thư viện có sẵn trong đường dẫn 'Android\sdk\build-tools'

###Cách Tạo fonts.xml (21v) và style.xml (21v) </br>
+ res => new => android resource file </br>
![create v21](https://cloud.githubusercontent.com/assets/13708331/16894575/b7a002f2-4b84-11e6-9885-da36e0181e1b.png)

###Cách Tạo drawable với đầy đủ kích thước 
+ bỏ hình drawable kích chuột phải vào hình chọn new => image asset </br>
![import into drawable](https://cloud.githubusercontent.com/assets/13708331/16894606/9465d518-4b85-11e6-9855-374c97349847.png)

#### kích cỡ 1 số loại
+ hdpi 48 x 48
+ mdpi 32 x32
+ xhdpi 64 x 64
+ xxhdpi 94 x 94




