# First-Android-App
Happy Birthday App
<RelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <ImageView
        android:src="@drawable/androidparty"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:scaleType="centerCrop"/>

    <TextView
        android:text="Happy Birthday John!"
        android:padding="20dp"
        android:fontFamily="sans-serif-light"
        android:textColor="@android:color/white"
        android:textSize="36sp"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content" />
    
    <TextView
        android:text="From Bogdan"
        android:padding="20dp"
        android:fontFamily="sans-serif-light"
        android:textColor="@android:color/white"
        android:textSize="36sp"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_alignParentRight="true" />

</RelativeLayout>
