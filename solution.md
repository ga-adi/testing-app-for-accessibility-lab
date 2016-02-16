Some features that need to be fixed:

 1. Forward arrow in bar chart needs a label.
```xml
<net.steamcrafted.materialiconlib.MaterialIconView
    ...
    android:contentDescription="Next arrow"/>
```

 2. Back arrow in bar chart needs a label.
 ```xml
 <net.steamcrafted.materialiconlib.MaterialIconView
     android:id="@+id/back"
     ...
     android:contentDescription="Back arrow"/>
 ```

 3. EditText in bar chart needs a hint label.
 ```xml
 <EditText
     ...
     android:hint="Search a zipcode"/>
 ```

 4. About page needs label for Facebook, Twitter, and Google+ icons.
 ```xml
 <ImageButton
   ...
     android:contentDescription="Connect with Facebook"
   />

 <ImageButton
     ...
     android:contentDescription="Connect with Twitter"
     />

 <ImageButton
     ...
     android:contentDescription="Connect with Google+"
     />
 ```

  5. Menu icons need talkback labels.
[I know this has to be done in Java, since these are tab bar icons, but I'm not sure how to go about it.]

  6. Icons in profile activity need labels.
  ```xml
  <ImageView
    ...
    android:contentDescription="Location icon"
    />

<ImageView
    ...
    android:contentDescription="Time icon"
    />

<ImageView
    ...
    android:contentDescription="Who icon"
    />

<ImageView
    ...
    android:contentDescription="What happened icon"
    />
  ```

  7. Custom toast icon needs a label.
  ```xml
  <ImageView
    ...
    android:contentDescription="Speakerphone icon"/>
```
