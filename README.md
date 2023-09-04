# med

```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:background="@drawable/background_fragments"
    tools:context=".SingleLabTest">
    
    <androidx.cardview.widget.CardView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        app:cardElevation="10dp"
        app:cardCornerRadius="8dp"
        android:layout_marginTop="20dp"
        android:padding="10dp"
        android:layout_margin="10dp">
        
        <RelativeLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content">

            <ImageView
                android:id="@+id/imageView"
                android:layout_width="match_parent"
                android:layout_height="200dp"
                android:src="@drawable/labtest2"
                android:scaleType="centerCrop"
                android:layout_marginBottom="8dp"
                android:elevation="4dp"
                />

            <TextView
                android:layout_below="@+id/imageView"
                android:id="@+id/tvLabTestName"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="Lab Test Name"
                android:layout_marginLeft="12dp"
                android:textStyle="bold"
                android:textSize="18sp"
                android:textColor="@color/black" 
                android:layout_marginTop="15dp"
                android:textAlignment="center"/>
            
        </RelativeLayout>
        
        
    </androidx.cardview.widget.CardView>

    <androidx.cardview.widget.CardView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        app:cardElevation="10dp"
        app:cardCornerRadius="8dp"
        android:layout_marginTop="20dp"
        android:padding="10dp"
        android:layout_margin="10dp">

        <RelativeLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content">

            

            <TextView
                android:id="@+id/textDec"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="This is the Lab Test Description This is the Lab Test Description This is the Lab Test Description This is the Lab Test Description This is the Lab Test Description"
                android:textAlignment="center"
                android:textSize="15sp"
                android:padding="12dp"/>

            <TextView
                android:layout_below="@id/textDec"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:text="Cost: KSHS 1000"
                android:layout_marginLeft="12dp"
                android:textStyle="bold"
                android:textSize="18sp"
                android:textColor="@color/black"
                android:layout_marginTop="15dp"
               />
            
            

        </RelativeLayout>


    </androidx.cardview.widget.CardView>

</LinearLayout>

```
