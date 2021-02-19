
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"

    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:gravity="center"
    android:background="@drawable/ic_bg"
    tools:context=".Final_Result">

    <ImageView
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="6"
        android:background="@drawable/ic_trophy_smaller"
        android:layout_gravity="center"
        android:layout_margin="14dp"
        />
    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:gravity="center"
        android:text="Hey Congratulations !!"
        android:textStyle="normal"
        android:layout_weight="1"
        android:textSize="28sp"
        android:textColor="#FFFFFF"
        android:layout_margin="14dp"
        />
    <TextView
        android:id="@+id/User_Name"
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="1"
        android:gravity="center"
        android:text="UserName"
        android:textStyle="normal"
        android:textSize="28sp"
        android:textColor="#DD2C00"
        android:layout_margin="7dp"
        />
    <TextView
        android:id="@+id/your_score"
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:gravity="center"
        android:layout_weight="1"
        android:text="score"
        android:textStyle="italic"
        android:textSize="22sp"
        android:textColor="#FFFFFF"
        android:layout_margin="14dp"
        />
    <Button
        android:id="@+id/btn_submit"
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:textSize="20sp"
        android:layout_weight="1"
        android:text="Finish"
        android:layout_margin="14dp"
        android:layout_marginBottom="25dp"
        android:background="#536DFE"

        />
</LinearLayout>
