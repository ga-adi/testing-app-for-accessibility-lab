Adityo - testing-app-for-accessibility-lab

#signup_fragment.xml

        <ImageButton
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:background="@android:color/transparent"
            android:id="@+id/facebook_button"
            android:src="@drawable/facebook"
            android:contentDescription="Click to sign in with facebook"
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
            android:contentDescription="Click to sign in with twitter"
            />

        <ImageButton
            android:id="@+id/googleplus_button"
            android:layout_width="0dp"
            android:layout_height="match_parent"
            android:layout_weight="1"
            android:src="@drawable/google"
            android:background="@android:color/transparent"
            android:contentDescription="Click to sign in with google"
            />


#profile_fragment.xml

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
                    android:contentDescription="This is a text field to enter your year of birth"/>

                    <CheckBox
                                    android:id="@+id/enable_geofence"
                                    android:layout_marginTop="16dp"
                                    android:text="@string/alert_detail"
                                    android:layout_width="match_parent"
                                    android:layout_height="wrap_content"
                                    android:contentDescription="This is a checkbox to enable notification settings" />

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
                                                        android:contentDescription="Click here if you are a lesbian"/>

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
                                                        android:contentDescription="Click here if you are a minor"/>

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
                                                        android:contentDescription="Click here if you identify with another category"/>

                                                </LinearLayout>
                                            </LinearLayout>


#pie_chart_fragment.xml

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
            android:contentDescription="Click to continue"
            />


#bar_chart_fragment.xml

<net.steamcrafted.materialiconlib.MaterialIconView
            android:id="@+id/back"
            android:layout_width="50dp"
            android:layout_height="50dp"
            android:layout_marginStart="10dp"
            app:materialIcon="arrow_left_bold"
            app:materialIconColor="#ffffff"
            android:contentDescription="Click here to go back"
            />


#stats_fragment.xml

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
            android:contentDescription="Enter zipcode here"/>
