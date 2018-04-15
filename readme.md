添加了shape.xml文件以显示圆形图案

<?xml version="1.0" encoding="utf-8"?>
    <shape
        xmlns:android="http://schemas.android.com/apk/res/android"
        android:shape="oval"
        android:useLevel="false">
        <solid android:color="#31a7dc"/>
        <size android:width="20dp"
            android:height="20dp"/>
    </shape>
    
在activity_main.xml中调用

<TextView  
    android:layout_width="50dp"
    android:layout_height="50dp"
    android:gravity="center"
    android:text="mon"
    android:textAllCaps="true"
    android:textColor="#111111"
    android:background="@drawable/shape"/>
                
添加button按钮及onclick事件
<RadioButton
    android:id="@+id/radioButton"
    android:layout_width="wrap_content"
    android:layout_height="34dp"
    android:layout_alignParentBottom="true"
    android:layout_alignLeft="@+id/tv_temperature"
    android:layout_marginBottom="27dp"
    android:onClick="btnClick"/>
