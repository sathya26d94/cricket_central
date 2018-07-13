# cricket_central
Simple Android App to demonstrate ListView &amp; FloatingActionButton

### Dependecies

```
compile 'com.android.support:appcompat-v7:26.0.1'
compile 'com.android.support:design:26.0.1'
```

## activity_main.xml

### ListView

```xml
<ListView
        android:id="@+id/list_view"
        android:layout_width="match_parent"
        android:layout_height="match_parent" />
 ```
 
 ### FloatingActionButton
 
 ```xml
 <android.support.design.widget.FloatingActionButton
        android:id="@+id/fab"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_alignParentRight="true"
        android:src="@android:drawable/arrow_up_float"
        android:visibility="gone"
        android:layout_marginRight="30dp"
        android:layout_marginBottom="30dp"/>
 ```
 
## listview_element.xml

```xml
<?xml version="1.0" encoding="utf-8"?>
<TextView xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent" android:layout_height="match_parent"
    android:textSize="30sp">
</TextView>
```

References 

https://developer.android.com/guide/topics/ui/floating-action-button
https://developer.android.com/reference/android/R.drawable


