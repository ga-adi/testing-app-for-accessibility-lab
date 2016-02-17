```java

###activity_details###

<ImageView
                android:contentDescription="Location details"
                android:id="@+id/where_image"
                android:layout_width="match_parent"
                android:layout_height="0dp"
                android:layout_weight="1"
                android:padding="27dp"
                android:src="@drawable/where"
                />


<!--Accessibility-->
                <TextView
                    android:id="@id/details_text"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:text="Location"
                    style="@style/detail_title"
                    android:contentDescription="Details of location"/>


###pie_chart_fragment.xml###
<TextView
                <!--added additional accessibility-->
                android:id="@+id/chart_header"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="@string/types_of_harassment"
                style="@style/chart_header"
                android:contentDescription="Types of harassment"/>


<ImageView
                android:contentDescription="Time details"
                android:id="@+id/when_image"
                android:layout_width="match_parent"
                android:layout_height="0dp"
                android:layout_weight="1"
                android:padding="27dp"
                android:src="@drawable/when"
                />
<ImageView
                android:contentDescription="Groups affected"
                android:id="@+id/who_image"
                android:layout_width="match_parent"
                android:layout_height="0dp"
                android:layout_weight="1"
                android:padding="27dp"
                android:src="@drawable/who"
                />

<ImageView
                android:contentDescription="What happened"
                android:id="@+id/what_image"
                android:layout_width="match_parent"
                android:layout_height="0dp"
                android:layout_weight="1"
                android:padding="27dp"
                android:src="@drawable/what"


<TextView
            <!--added additional accessibility-->
                android:id="@+id/no_harassment_message"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="@string/no_harassment"
                style="@style/no_harassment_message"
                android:contentDescription="No harassment"/>


###bar_chart_fragment###

   <TextView
                android:contentDescription="no harassment"
                android:id="@+id/no_harassment_message_bar"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="@string/no_harassment"
                style="@style/no_harassment_message"
                />

            <TextView
                android:contentDescription="Groups of people affected"
                android:id="@+id/chart_header"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="@string/groups"
                style="@style/chart_header" />


###custom_toast###

    <TextView android:id="@+id/text"
        android:contentDescription="Thanks for adding your voice to the movement"
        android:text="\nThanks for adding your voice to the movement.\n Stay tuned for updates!\n"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textColor="#FFF"
        android:fontFamily="sans-serif-thin"
        android:paddingLeft="10dp" />

    <ImageView
        android:contentDescription="Thanks for adding your voice to the movement"
        android:layout_width="50dp"
        android:layout_height="50dp"
        android:src="@drawable/smallwhitelogo"
        android:paddingTop="10dp" />

###stats_fragment###

<EditText
            android:contentDescription="location"
            android:id="@+id/zipcode"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_gravity="center_vertical"
            android:layout_weight="8"
            android:inputType="number"
            android:maxLength="5"
            android:textSize="18sp"
            android:focusable="true"/>

###profile_fragment###

<EditText
                    android:contentDescription="year of birth"
                    android:id="@+id/year"
                    android:layout_width="match_parent"
                    android:layout_height="match_parent"
                    android:hint="@string/birth_year"
                    android:inputType="number"
                    android:maxLength="4"
                    android:textColor="#000000"
                    android:textColorHint="#363636"
                    android:focusable="true"/>
            </android.support.design.widget.TextInputLayout>


<CheckBox
                android:contentDescription="harassment activity"
                android:id="@+id/enable_geofence"
                android:layout_marginTop="16dp"
                android:text="@string/alert_detail"
                android:layout_width="match_parent"
                android:layout_height="wrap_content" />

<ToggleButton
                    android:contentDescription="Man"
                    android:id="@+id/man"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginRight="3dp"
                    android:textOff="Man"
                    android:textOn="Man" />

                <ToggleButton
                    android:contentDescription="Woman"
                    android:id="@+id/woman"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginLeft="3dp"
                    android:layout_marginRight="3dp"
                    android:textOff="Woman"
                    android:textOn="Woman" />

                <ToggleButton
                    android:contentDescription="Lesbian"
                    android:id="@+id/lesbian"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginLeft="3dp"
                    android:textOff="Lesbian"
                    android:textOn="Lesbian" />


<ToggleButton
                    android:contentDescription="Colored person"
                    android:id="@+id/poc"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginRight="3dp"
                    android:textOff="Person of Color"
                    android:textOn="Person of Color" />

                <ToggleButton
                    android:contentDescription="Transgender"
                    android:id="@+id/trans"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginLeft="3dp"
                    android:textOff="Transgender"
                    android:textOn="Transgender" />


<ToggleButton
                    android:contentDescription="gay"
                    android:id="@+id/gay"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginRight="3dp"
                    android:textOff="Gay"
                    android:textOn="Gay" />

                <ToggleButton
                    android:contentDescription="bisexual"
                    android:id="@+id/bisexual"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginLeft="3dp"
                    android:layout_marginRight="3dp"
                    android:textOff="Bisexual"
                    android:textOn="Bisexual" />

                <ToggleButton
                    android:contentDescription="Minor"
                    android:id="@+id/minor"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginLeft="3dp"
                    android:textOff="Minor"
                    android:textOn="Minor" />


<ToggleButton
                    android:contentDescription="queer"
                    android:id="@+id/queer"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginRight="3dp"
                    android:textOff="Queer"
                    android:textOn="Queer" />

                <ToggleButton
                    android:contentDescription="other"
                    android:id="@+id/other"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    style="@style/toggle_button"
                    android:layout_marginLeft="3dp"
                    android:textOff="Other"
                    android:textOn="Other" />

<Button
            android:contentDescription="logout"
            android:id="@+id/log_out"
            android:text="Log Out"
            android:layout_gravity="center"
            android:layout_width="wrap_content"
            android:layout_height="0dp"
            android:textSize="15dp"
            android:padding="20dp"
            style="@style/button"
            android:layout_weight="2"/>

###Signup Fragment###
<TextView
        android:contentDescription="Login"
        android:id="@id/blazon"
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="0.5"
        android:text="Log in with"
        android:gravity="center|bottom"
        android:textColor="@color/text_white"
        android:fontFamily="sans-serif-light"
        android:textSize="22sp"/>


```