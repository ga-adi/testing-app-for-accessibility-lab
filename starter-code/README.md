##Changes

1. EditText (Edit Box) located in 'chart' tab, meant to search by Zip Code.
```xml
 android:id="@+id/zipcode"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_gravity="center_vertical"
            android:layout_weight="8"
            android:inputType="number"
            android:maxLength="5"
            android:textSize="18sp"
            android:focusable="true"
            android:contentDescription="Search by zipcode" <-- Added Code -->
```
2. Bold Right Arrow located in 'chart' tab, used to navigate through. Located at bottom right.
```xml
android:id="@+id/back"
            android:layout_width="50dp"
            android:layout_height="50dp"
            android:layout_marginStart="10dp"
            android:contentDescription="Back Button" <-- Added Code -->
            app:materialIcon="arrow_left_bold"
            app:materialIconColor="#ffffff"
```
3. Bold Left Arrow located in 'chart' tab, used to navigate through. Located at bottom left.
```xml
android:id="@+id/next"
            android:layout_width="50dp"
            android:layout_height="50dp"
            android:layout_alignParentEnd="true"
            android:layout_centerHorizontal="true"
            android:layout_centerVertical="true"
            android:layout_marginEnd="15dp"
            android:contentDescription="Forward button"  <-- Added Code -->
            app:materialIcon="arrow_right_bold"
            app:materialIconColor="#ffffff"
```
4. In 'Add New Shame' dialog, the time editor was generic description. 
```xml
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:orientation="vertical" android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:contentDescription="Enter Month, Day, and Year above. Enter Hour, Minute, AM/PM Below"> <-- Added Code -->
```