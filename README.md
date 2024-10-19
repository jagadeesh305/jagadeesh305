<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <Button
        android:id="@+id/scan_button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Scan and Read"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="100dp" />

    <ImageView
        android:id="@+id/image_view"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_below="@id/scan_button"
        android:contentDescription="Scanned Image" />
</RelativeLayout>
