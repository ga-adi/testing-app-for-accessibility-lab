signup_fragments.xml (the logos)
```xml
        <ImageButton
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:background="@android:color/transparent"
            android:id="@+id/facebook_button"
            android:src="@drawable/facebook"
            android:contentDescription="CLICK HERE TO SIGN IN WITH FACEBOOK"
            />

        <ImageButton
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:layout_marginLeft="10dp"
            android:layout_marginRight="10dp"
            android:id="@+id/twitter_button"
            android:src="@drawable/twitter"
            android:background="@android:color/transparent"
            android:contentDescription="CLICK HERE TO SIGN IN WITH TWITTER"
            />

        <ImageButton
            android:id="@+id/googleplus_button"
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:src="@drawable/google"
            android:background="@android:color/transparent"
            android:contentDescription="CLICK HERE TO SIGN IN WITH GOOGLE PLUS"
            />
               
stats_fragment.xml

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
            android:contentDescription="enter zip code here"/>


pie_chart_fragment.xml
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
            android:contentDescription="Press this arrow to see groups of people percent"
            />

```

profile_fragment.xml
```xml
                <EditText
                    android:id="@+id/year"
                    android:layout_width="match_parent"
                    android:layout_height="match_parent"
                    android:hint="@string/birth_year"
                    android:inputType="number"
                    android:maxLength="4"
                    android:textColor="#000000"
                    android:textColorHint="#363636"
                    android:focusable="true"
                    android:contentDescription="enter  year here"/>
                    
                                <CheckBox
                                    android:id="@+id/enable_geofence"
                                    android:layout_marginTop="16dp"
                                    android:text="@string/alert_detail"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content" 
                                    android:contentDescription="check here to notify me when entering high risk area" />


```
activity_details.xml
```xml

            <ImageView
                android:id="@+id/where_image"
                android:layout_width="match_parent"
                android:layout_height="0dp"
                android:layout_weight="1"
                android:padding="27dp"
                android:src="@drawable/where"
                android:contentDescription="click here to learn mre about location"
                />

            <ImageView
                android:id="@+id/when_image"
                android:layout_width="match_parent"
                android:layout_height="0dp"
                android:layout_weight="1"
                android:padding="27dp"
                android:src="@drawable/when"
                android:contentDescription="Click here to learn more about date"
                />

            <ImageView
                android:id="@+id/who_image"
                android:layout_width="match_parent"
                android:layout_height="0dp"
                android:layout_weight="1"
                android:padding="27dp"
                android:src="@drawable/who"
                android:contentDescription="Click here to learn more about who"
                />

            <ImageView
                android:id="@+id/what_image"
                android:layout_width="match_parent"
                android:layout_height="0dp"
                android:layout_weight="1"
                android:padding="27dp"
                android:src="@drawable/what"
                android:contentDescription="click here to learn more about what happened"
                />
```

bar_chart_fragment.xml
```xml
        <net.steamcrafted.materialiconlib.MaterialIconView
            android:id="@+id/back"
            android:layout_width="50dp"
            android:layout_height="50dp"
            android:layout_marginStart="10dp"
            app:materialIcon="arrow_left_bold"
            app:materialIconColor="#ffffff"
            android:contentDescription="Back to types of harassement"
            />
```