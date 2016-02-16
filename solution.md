##1. map_fragment.xml
```xml
<Button
            android:id="@+id/filter"
            style="@style/button"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:layout_weight="3"
            android:text="Filter"
            android:textStyle="bold"
            android:textColor="@color/primary"
            android:contentDescription="This is the filter button"/>
```
```xml
<AutoCompleteTextView
                android:id="@+id/search"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_gravity="center_vertical"
                android:hint="Search by location                                     "
                android:imeOptions="actionGo"
                android:textSize="18dp"
                android:focusable="true"
                android:contentDescription="This is a text field for address"/>
```

##2. profile fragment.xml
```xml
<CheckBox
                android:id="@+id/enable_geofence"
                android:layout_marginTop="16dp"
                android:text="@string/alert_detail"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:contentDescription="This is a checkbox for notification setting"/>
```
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
                    android:contentDescription="This is a text field for your year of birth"/>
```

##3. profile_fragment.xml
```xml

            <com.github.mikephil.charting.charts.BarChart
                android:id="@+id/bar_chart"
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:layout_below="@id/chart_header"
                android:background="#FFFFFF"
                android:contentDescription="This is a bar chart for the group of people"/>
```
```xml
<net.steamcrafted.materialiconlib.MaterialIconView
            android:id="@+id/back"
            android:layout_width="50dp"
            android:layout_height="50dp"
            android:layout_marginStart="10dp"
            app:materialIcon="arrow_left_bold"
            app:materialIconColor="#ffffff"
            android:contentDescription="Button for going back to the pie chart"
            />
```
```xml
                <ToggleButton
                    android:id="@+id/man"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginRight="3dp"
                    android:textOff="Man"
                    android:textOn="Man"
                    android:contentDescription="Click here if you are a man"/>

                <ToggleButton
                    android:id="@+id/woman"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginLeft="3dp"
                    android:layout_marginRight="3dp"
                    android:textOff="Woman"
                    android:textOn="Woman"
                    android:contentDescription="Click here if you are a woman"/>

                <ToggleButton
                    android:id="@+id/lesbian"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginLeft="3dp"
                    android:textOff="Lesbian"
                    android:textOn="Lesbian"
                    android:contentDescription="Click here if you are lesbian"/>

                </LinearLayout>

            <LinearLayout
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_gravity="center"
                android:layout_marginTop="7dp"
                android:orientation="horizontal">

                <ToggleButton
                    android:id="@+id/poc"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginRight="3dp"
                    android:textOff="Person of Color"
                    android:textOn="Person of Color"
                    android:contentDescription="Click here if you are a person of color"/>

                <ToggleButton
                    android:id="@+id/trans"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginLeft="3dp"
                    android:textOff="Transgender"
                    android:textOn="Transgender"
                    android:contentDescription="Click here if you are a transgender"/>

            </LinearLayout>

            <LinearLayout
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_gravity="center"
                android:layout_marginTop="7dp"
                android:orientation="horizontal">

                <ToggleButton
                    android:id="@+id/gay"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginRight="3dp"
                    android:textOff="Gay"
                    android:textOn="Gay"
                    android:contentDescription="Click here if you are gay"/>

                <ToggleButton
                    android:id="@+id/bisexual"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginLeft="3dp"
                    android:layout_marginRight="3dp"
                    android:textOff="Bisexual"
                    android:textOn="Bisexual"
                    android:contentDescription="Click here if you are bisexual"/>

                <ToggleButton
                    android:id="@+id/minor"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginLeft="3dp"
                    android:textOff="Minor"
                    android:textOn="Minor"
                    android:contentDescription="Click here if you are minor"/>

            </LinearLayout>

            <LinearLayout
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_gravity="center"
                android:layout_marginTop="7dp"
                android:orientation="horizontal">

                <ToggleButton
                    android:id="@+id/queer"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginRight="3dp"
                    android:textOff="Queer"
                    android:textOn="Queer"
                    android:contentDescription="Click here if you are a queer"/>

                <ToggleButton
                    android:id="@+id/other"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginLeft="3dp"
                    android:textOff="Other"
                    android:textOn="Other"
                    android:contentDescription="Click here if you are in another category"/>
```

## 4. signup_fragment.xml
```xml
        <ImageButton
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:background="@android:color/transparent"
            android:id="@+id/facebook_button"
            android:src="@drawable/facebook"
            android:contentDescription="Log in with facebook"
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
            android:contentDescription="Log in with twitter"
            />

        <ImageButton
            android:id="@+id/googleplus_button"
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:src="@drawable/google"
            android:background="@android:color/transparent"
            android:contentDescription="Log in with google plus"
            />
```
##5. stats_fragment.xml
```xml
<Button
            android:id="@+id/overview"
            style="@style/button"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:layout_weight="4"
            android:text="General Overview" 
            android:contentDescription="Button for general overview"/>

        <ImageView
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_gravity="center"
            android:layout_weight="2"
            android:layout_marginRight="5dp"
            android:src="@drawable/search"
            android:contentDescription="@string/zipcode_description"/>

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
            android:contentDescription="Enter your zipcode here"/>
,,,
##6. activity_details.xml
<ImageView
                android:id="@+id/where_image"
                android:layout_width="match_parent"
                android:layout_height="0dp"
                android:layout_weight="1"
                android:padding="27dp"
                android:src="@drawable/where"
                android:contentDescription="This image contains a globe icon"
                />

            <ImageView
                android:id="@+id/when_image"
                android:layout_width="match_parent"
                android:layout_height="0dp"
                android:layout_weight="1"
                android:padding="27dp"
                android:src="@drawable/when"
                android:contentDescription="This image contains a clock icon"
                />

            <ImageView
                android:id="@+id/who_image"
                android:layout_width="match_parent"
                android:layout_height="0dp"
                android:layout_weight="1"
                android:padding="27dp"
                android:src="@drawable/who"
                android:contentDescription="This image contains a person icon"
                />

            <ImageView
                android:id="@+id/what_image"
                android:layout_width="match_parent"
                android:layout_height="0dp"
                android:layout_weight="1"
                android:padding="27dp"
                android:src="@drawable/what"
                android:contentDescription="This image contains an alert icon"
                />
```
