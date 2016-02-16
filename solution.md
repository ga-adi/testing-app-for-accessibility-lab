#activity_details.xml
  No changes required, all details are read out properly.

#bar_chart_fragment.xml
```xml
<net.steamcrafted.materialiconlib.MaterialIconView
    android:id="@+id/back"
...
    android:contentDescription="Back"
    />

```

#custom_toast.xml
  No changes required.

#map_fragment.xml
  Nada

#pie_chart_fragment.xml
```xml
<net.steamcrafted.materialiconlib.MaterialIconView
...
    android:contentDescription="Continue"
    />
```

#signup_fragment.xml

```xml

<ImageButton
...
     android:id="@+id/facebook_button"
     android:src="@drawable/facebook"
     android:contentDescription="Facebook"
     />

 <ImageButton
...
     android:id="@+id/twitter_button"
     android:src="@drawable/twitter"
     android:background="@android:color/transparent"
     android:contentDescription="Twitter"
     />

 <ImageButton
...
     android:src="@drawable/google"
     android:background="@android:color/transparent"
     android:contentDescription="Google Plus"
     />

```

#stats_fragment.xml
  Nada



CAN'T FIND:

Main menu:
  Tool bar has no announcements: Maps icon, Graph icon, Person icon
    Found TabLayout adding the icons in MainActivity.java, but can't identify and apply contentDescription.

  Alert buttons on map don't read and snackbars opened by them don't read.
    Google maps issue?  We can't apply contentDescription?
