Mike Kwon Accessibility Lab - solution code


***add content descriptions to the three TabLayout menu buttons declared in the MainActivity Java

```java
    TabLayout tabLayout = (TabLayout) findViewById(R.id.tabs);
    tabLayout.setTabMode(TabLayout.MODE_FIXED);
    tabLayout.setTabGravity(TabLayout.GRAVITY_CENTER);
    tabLayout.addTab(tabLayout.newTab().setIcon(R.drawable.map).setContentDescription("Button to navigate to map screen"));
    tabLayout.addTab(tabLayout.newTab().setIcon(R.drawable.stats).setContentDescription("Button to navigate to stats screen"));
    tabLayout.addTab(tabLayout.newTab().setIcon(R.drawable.profile).setContentDescription("Button to navigate to profile screen"));
```

***added xml hint to the EditText box in the chart tab

```xml
	<EditText
		android:id="@+id/zipcode"
		android:layout_width="0dp"
		android:layout_height="wrap_content"
    	android:layout_gravity="center_vertical"
    	android:layout_weight="8"
    	android:inputType="number"
    	android:maxLength="5"
    	android:textSize="18sp"
    	android:focusable="true"
    	android:hint="Enter zipcode here"/>
```

***added contentDescription to back button in the chart tab

```xml
    <net.steamcrafted.materialiconlib.MaterialIconView
    	android:id="@+id/back"
	    android:layout_width="50dp"
    	android:layout_height="50dp"
    	android:layout_marginStart="10dp"
    	app:materialIcon="arrow_left_bold"
    	app:materialIconColor="#ffffff"
    	android:contentDescription="Back Button"/>
```

***added contentDescription to forward navigation button in the pie chart fragment

```xml
	<net.steamcrafted.materialiconlib.MaterialIconView
    	android:id="@+id/next"
        android:layout_width="50dp"
        android:layout_height="50dp"
        android:layout_alignParentEnd="true"
        android:layout_centerHorizontal="true"
        android:layout_centerVertical="true"
        android:layout_marginEnd="15dp"
        app:materialIcon="arrow_right_bold"
        app:materialIconColor="#ffffff"
        android:contentDescription="Forward navigation button" />
```