bar_chart_fragment.xml
```xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:id="@+id/a"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical">

    <android.support.v7.widget.CardView xmlns:card_view="http://schemas.android.com/apk/res-auto"
        android:id="@+id/card_view"
        style="@style/card"
        card_view:cardBackgroundColor="#FFFFFF"
        card_view:cardCornerRadius="10dp"
        card_view:cardElevation="6dp"
        android:contentDescription="Percentage of harassment among groups of people">

        <RelativeLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent">

            <TextView
                android:id="@+id/no_harassment_message_bar"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="@string/no_harassment"
                style="@style/no_harassment_message"/>

            <TextView
                android:id="@+id/chart_header"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="@string/groups"
                style="@style/chart_header" />


            <com.github.mikephil.charting.charts.BarChart
                android:id="@+id/bar_chart"
                android:layout_width="match_parent"
                android:layout_height="match_parent"
                android:layout_below="@id/chart_header"
                android:background="#FFFFFF"
                android:contentDescription="Bar chart of the harassment percentages."/>

        </RelativeLayout>

    </android.support.v7.widget.CardView>

    <RelativeLayout
        android:id="@+id/parent"
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="0.7"
        android:layout_marginBottom="10dp"
        android:orientation="horizontal">

        <net.steamcrafted.materialiconlib.MaterialIconView
            android:id="@+id/back"
            android:layout_width="50dp"
            android:layout_height="50dp"
            android:layout_marginStart="10dp"
            app:materialIcon="arrow_left_bold"
            app:materialIconColor="#ffffff"
            android:contentDescription="Button to go back to pie chart"
            />

        <TextView
            android:id="@+id/instances"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_alignParentEnd="true"
            android:layout_centerVertical="true"
            android:layout_marginEnd="30dp"
            android:text="@string/total_instances"
            android:textColor="@color/text_white"
            android:textSize="18sp" />

    </RelativeLayout>

</LinearLayout>

```
custom_toast.xml
```xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:id="@+id/toast_layout_root"
    android:orientation="vertical"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:padding="8dp"
    >

    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        android:background="@color/primary_dark">

    <TextView android:id="@+id/text"
        android:text="\nThanks for adding your voice to the movement.\n Stay tuned for updates!\n"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textColor="#FFF"
        android:fontFamily="sans-serif-thin"
        android:paddingLeft="10dp" />

    <ImageView
        android:layout_width="50dp"
        android:layout_height="50dp"
        android:src="@drawable/smallwhitelogo"
        android:paddingTop="10dp"
        android:contentDescription="Thumbs down image logo"/>
    </LinearLayout>
</LinearLayout>
```

profile_fragment.xml
```xml
<?xml version="1.0" encoding="utf-8"?>
<ScrollView xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:contentDescription="@string/profile_fragment">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0dp"
            android:background="@drawable/polygons"
            android:layout_weight="2"
            android:padding="20dp"
            android:orientation="horizontal">

            <de.hdodenhof.circleimageview.CircleImageView
                android:id="@+id/profile_image"
                android:layout_width="0dp"
                android:layout_height="200dp"
                android:layout_marginLeft="10dp"
                android:layout_weight="1"
                android:src="@drawable/logo_white"
                app:border_color="@color/accent"
                app:border_width="2dp"
                android:contentDescription="@string/profile_image_container"/>

            <TextView
                android:id="@+id/profile_text"
                android:layout_width="0dp"
                android:textColor="@color/text_white"
                android:layout_height="match_parent"
                android:layout_marginRight="10dp"
                android:layout_weight="1"
                android:gravity="bottom|right"
                android:text="Profile"
                android:textSize="40sp" />

        </LinearLayout>

        <View style="@style/Divider"/>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0dp"
            android:padding="28dp"
            android:layout_weight="2"
            android:orientation="vertical">

            <TextView
                android:id="@id/profile_text"
                style="@style/profile_text"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="Age" />

            <android.support.design.widget.TextInputLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                app:hintTextAppearance="@style/TextAppearence.App.TextInputLayout">

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
                    android:contentDescription="Enter the year of your birth. Edit text box."/>
            </android.support.design.widget.TextInputLayout>

        </LinearLayout>

        <View style="@style/Divider"/>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0dp"
            android:padding="28dp"
            android:layout_weight="2"
            android:orientation="vertical">

            <TextView
                android:id="@id/profile_text"
                style="@style/profile_text"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="@string/blazon_alert" />

            <CheckBox
                android:id="@+id/enable_geofence"
                android:layout_marginTop="16dp"
                android:text="@string/alert_detail"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:contentDescription="Check off if you want notifications when entering areas with high harassment reports."/>

        </LinearLayout>

        <View style="@style/Divider"/>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0dp"
            android:layout_weight="4"
            android:padding="28dp"
            android:orientation="vertical">

            <TextView
                android:id="@id/profile_text"
                style="@style/profile_text"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="I identify as" />

            <LinearLayout
                android:layout_width="wrap_content"
                android:layout_height="match_parent"
                android:layout_marginTop="16dp"
                android:layout_gravity="center"
                android:orientation="horizontal">

                <ToggleButton
                    android:id="@+id/man"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginRight="3dp"
                    android:textOff="Man"
                    android:textOn="Man"
                    android:contentDescription="Select if you are a man"/>

                <ToggleButton
                    android:id="@+id/woman"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginLeft="3dp"
                    android:layout_marginRight="3dp"
                    android:textOff="Woman"
                    android:textOn="Woman"
                    android:contentDescription="Select if you are a woman."/>

                <ToggleButton
                    android:id="@+id/lesbian"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginLeft="3dp"
                    android:textOff="Lesbian"
                    android:textOn="Lesbian"
                    android:contentDescription="Select if you are Lesbian"/>

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
                    android:contentDescription="Select if you are a person of color"/>

                <ToggleButton
                    android:id="@+id/trans"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginLeft="3dp"
                    android:textOff="Transgender"
                    android:textOn="Transgender"
                    android:contentDescription="Select if you are transgender"/>

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
                    android:contentDescription="Select if you are gay"/>

                <ToggleButton
                    android:id="@+id/bisexual"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginLeft="3dp"
                    android:layout_marginRight="3dp"
                    android:textOff="Bisexual"
                    android:textOn="Bisexual"
                    android:contentDescription="Select if you are bi"/>

                <ToggleButton
                    android:id="@+id/minor"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginLeft="3dp"
                    android:textOff="Minor"
                    android:textOn="Minor"
                    android:contentDescription="Select if you are a minor"/>

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
                    android:contentDescription="Select if you are a queer"/>

                <ToggleButton
                    android:id="@+id/other"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginLeft="3dp"
                    android:textOff="Other"
                    android:textOn="Other"
                    android:contentDescription="Select if you consider yourself any other category"/>

            </LinearLayout>
        </LinearLayout>

        <View style="@style/Divider"/>

        <Button
            android:id="@+id/log_out"
            android:text="Log Out"
            android:layout_gravity="center"
            android:layout_width="wrap_content"
            android:layout_height="0dp"
            android:textSize="15dp"
            android:padding="20dp"
            style="@style/button"
            android:layout_weight="2"
            android:contentDescription="Log out button."/>
    </LinearLayout>
</ScrollView>
```

signup_fragment.xml
```xml
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:background="@drawable/gradient"
    tools:context="charlyn23.c4q.nyc.projectx.SignUpFragment">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="6"
        android:gravity="center"
        android:orientation="vertical">

        <ImageView
            android:id="@+id/name"
            android:layout_width="159dp"
            android:layout_height="159dp"
            android:layout_gravity="center"
            android:layout_marginBottom="25dp"
            android:src="@drawable/logo_large"
            android:contentDescription="@string/app_logo"/>

        <TextView
            android:id="@+id/blazon"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:gravity="center"
            android:text="Blazon"
            android:textStyle="bold"
            android:textColor="@android:color/black"
            android:textSize="40sp" />

        <TextView
            android:id="@id/blazon"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginTop="10dp"
            android:gravity="center"
            android:text="Come Together.\n Voice the Movement"
            android:textSize="20sp"/>

    </LinearLayout>

    <TextView
        android:id="@id/blazon"
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="0.5"
        android:text="Log in with"
        android:gravity="center|bottom"
        android:textColor="@color/text_white"
        android:fontFamily="sans-serif-light"
        android:textSize="22sp"/>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="2.3"
        android:gravity="center"
        android:layout_marginLeft="30dp"
        android:layout_marginRight="30dp"
        android:orientation="horizontal">

        <ImageButton
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:background="@android:color/transparent"
            android:id="@+id/facebook_button"
            android:src="@drawable/facebook"
            android:contentDescription="Sign up with your Facebook account"
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
            android:contentDescription="Sign up with your Twitter account"
            />

        <ImageButton
            android:id="@+id/googleplus_button"
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:src="@drawable/google"
            android:background="@android:color/transparent"
            android:contentDescription="Sign up with your Google Plus account"
            />

    </LinearLayout>
</LinearLayout>
```

stats_fragment.xml
```xml
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="0dp"
    android:background="@drawable/gradient"
    android:descendantFocusability="beforeDescendants"
    android:orientation="vertical"
    android:contentDescription="@string/stats_data_fragment">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="1"
        android:orientation="horizontal">

        <Button
            android:id="@+id/overview"
            style="@style/button"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_gravity="center"
            android:layout_weight="4"
            android:text="General Overview"
            android:contentDescription="See the general overview"/>

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
            android:contentDescription="Enter your zip code."/>

    </LinearLayout>

    <android.support.v4.view.ViewPager
        android:id="@+id/inner_pager"
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="8" />

</LinearLayout>

```

activity_details.xml
```xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:id="@+id/scene_container">

    <TextView
        android:id="@+id/details_text"
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="3"
        android:text="Details"
        android:textColor="@color/text_white"
        android:textSize="35dp"
        android:gravity="right|bottom"
        android:padding="20dp"
        android:background="@drawable/polygons" />

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="7"
        android:orientation="horizontal">

        <LinearLayout
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="6"
            android:orientation="vertical">

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="0dp"
                android:layout_weight="1"
                android:layout_marginTop="25dp"
                android:layout_marginLeft="25dp"
                android:layout_marginBottom="7dp"
                android:orientation="vertical">

                <TextView
                    android:id="@id/details_text"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:text="Location"
                    style="@style/detail_title"/>

                <TextView
                    android:id="@+id/where"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    style="@style/detail_info"/>
            </LinearLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="0dp"
                android:layout_weight="1"
                android:layout_marginTop="7dp"
                android:layout_marginLeft="25dp"
                android:layout_marginBottom="7dp"
                android:orientation="vertical">

                <TextView
                    android:id="@id/details_text"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:text="Time"
                    style="@style/detail_title"/>

                <TextView
                    android:id="@+id/when"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    style="@style/detail_info"/>
            </LinearLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="0dp"
                android:layout_weight="1"
                android:layout_marginTop="7dp"
                android:layout_marginLeft="25dp"
                android:layout_marginBottom="7dp"
                android:orientation="vertical">

                <TextView
                    android:id="@id/details_text"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:text="Group Effected"
                    style="@style/detail_title"/>

                <TextView
                    android:id="@+id/who"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    style="@style/detail_info"/>
            </LinearLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="0dp"
                android:layout_weight="1"
                android:layout_marginTop="7dp"
                android:layout_marginLeft="25dp"
                android:layout_marginBottom="7dp"
                android:orientation="vertical">

                <TextView
                    android:id="@id/details_text"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:text="What Happened"
                    style="@style/detail_title"/>

                <TextView
                    android:id="@+id/what"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    style="@style/detail_info"/>
            </LinearLayout>

        </LinearLayout>

        <LinearLayout
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="2"
            android:layout_marginBottom="10dp"
            android:paddingLeft="9dp"
            android:paddingRight="9dp"
            android:paddingBottom="13dp"
            android:orientation="vertical">

            <ImageView
                android:id="@+id/where_image"
                android:layout_width="match_parent"
                android:layout_height="0dp"
                android:layout_weight="1"
                android:padding="27dp"
                android:src="@drawable/where"
                android:contentDescription="Where is this?"
                />

            <ImageView
                android:id="@+id/when_image"
                android:layout_width="match_parent"
                android:layout_height="0dp"
                android:layout_weight="1"
                android:padding="27dp"
                android:src="@drawable/when"
                android:contentDescription="When is this?"
                />

            <ImageView
                android:id="@+id/who_image"
                android:layout_width="match_parent"
                android:layout_height="0dp"
                android:layout_weight="1"
                android:padding="27dp"
                android:src="@drawable/who"
                android:contentDescription="Who is this?"
                />

            <ImageView
                android:id="@+id/what_image"
                android:layout_width="match_parent"
                android:layout_height="0dp"
                android:layout_weight="1"
                android:padding="27dp"
                android:src="@drawable/what"
                android:contentDescription="What is this?"
                />

        </LinearLayout>
    </LinearLayout>
</LinearLayout>
```

map_fragment.xml
```xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:id="@+id/scene_container"
    >

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_gravity="right"
        android:background="@color/text_white"
        android:orientation="horizontal">

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
            android:contentDescription="Filter the search results"/>

        <ImageView
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_gravity="center"
            android:layout_weight="2"
            android:padding="2dp"
            android:layout_marginRight="5dp"
            android:src="@drawable/search"
            android:contentDescription="@string/description_find_location"/>

        <HorizontalScrollView
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:gravity="center"
            android:layout_weight="9"
            android:requiresFadingEdge="horizontal"
            android:scrollbars="none">

            <AutoCompleteTextView
                android:id="@+id/search"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_gravity="center_vertical"
                android:hint="Search by location                                     "
                android:imeOptions="actionGo"
                android:textSize="18dp"
                android:focusable="true"/>

        </HorizontalScrollView>

    </LinearLayout>

    <RelativeLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="vertical">

        <fragment xmlns:android="http://schemas.android.com/apk/res/android"
            android:id="@+id/map"
            android:name="com.google.android.gms.maps.SupportMapFragment"
            android:layout_width="match_parent"
            android:layout_height="match_parent" />

        <android.support.design.widget.FloatingActionButton
            android:id="@+id/add_shame"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:src="@drawable/addshame"
            android:visibility="invisible"
            app:backgroundTint="@color/primary"
            app:elevation="6dp"
            app:pressedTranslationZ="6dp"
            app:rippleColor="@color/primary_dark"
            android:contentDescription="@string/add_instance"/>

    </RelativeLayout>
</LinearLayout>
```

