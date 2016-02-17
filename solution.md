''' xml
<!-- signup_fragment.xml -->

<ImageView
android:contentDescription="Blazon Logo"/>

<ImageButton
           android:layout_width="0dp"
           android:layout_height="match_parent"
           android:layout_weight="1"
           android:background="@android:color/transparent"
           android:id="@+id/facebook_button"
           android:src="@drawable/facebook"
           android:contentDescription="Sign up with your Facebook account."/>

       <ImageButton
           android:layout_width="0dp"
           android:layout_height="match_parent"
           android:layout_weight="1"
           android:layout_marginLeft="10dp"
           android:layout_marginRight="10dp"
           android:id="@+id/twitter_button"
           android:src="@drawable/twitter"
           android:background="@android:color/transparent"
           android:contentDescription="Sign up with your Twitter account."/>

       <ImageButton
           android:id="@+id/googleplus_button"
           android:layout_width="0dp"
           android:layout_height="match_parent"
           android:layout_weight="1"
           android:src="@drawable/google"
           android:background="@android:color/transparent"
           android:contentDescription="Sign up with your Google Plus account."/>

<!-- End of signup_fragment.xml -->


<!-- In pie_chart_fragment.xml -->
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
            android:contentDescription="Go to bar chart"/>
<!-- End pie_chart_fragment.xml -->



<!-- In bar_chart_fragment.xml -->
<net.steamcrafted.materialiconlib.MaterialIconView
    android:id="@+id/back"
    android:layout_width="50dp"
    android:layout_height="50dp"
    android:layout_marginStart="10dp"
    app:materialIcon="arrow_left_bold"
    app:materialIconColor="#ffffff"
    android:contentDescription="Go to pie chart"/>
<!-- End bar_chart_fragment.xml -->

'''
