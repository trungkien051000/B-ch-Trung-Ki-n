<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">


    <ImageView
        android:id="@+id/imageView1"
        android:layout_width="120dp"
        android:layout_height="150dp"
        android:layout_alignParentTop="true"
        android:layout_alignParentEnd="true"
        android:layout_alignParentRight="true"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="15dp"
        android:layout_marginEnd="146dp"
        android:layout_marginRight="146dp"
        app:srcCompat="@drawable/LogoGarena"
        tools:ignore="ContentDescription" />

    <TextView
        android:id="@+id/textView"
        android:layout_width="107dp"
        android:layout_height="wrap_content"
        android:layout_alignParentTop="true"
        android:layout_alignParentEnd="true"
        android:layout_alignParentRight="true"
        android:layout_marginTop="150dp"
        android:layout_marginEnd="146dp"
        android:layout_marginRight="146dp"
        android:text="@string/garena"
        android:textColor="@android:color/holo_red_light"
        android:textSize="30dp"
        />

    <EditText
        android:id="@+id/editText1"
        android:layout_width="275dp"
        android:layout_height="30dp"
        android:layout_alignParentStart="true"
        android:layout_alignParentLeft="true"
        android:layout_alignParentTop="true"
        android:layout_centerHorizontal="true"
        android:layout_marginStart="80dp"
        android:layout_marginLeft="80dp"
        android:layout_marginTop="228dp"
        android:background="#11000000"
        android:drawableLeft="@drawable/ic_action_user"
        android:ems="10"
        android:inputType="textPersonName"
        android:text="Tên đăng nhập/E-mail"
        android:textSize="20dp" />

    <EditText
        android:id="@+id/editText"
        android:layout_width="275dp"
        android:layout_height="30dp"
        android:layout_below="@id/editText1"
        android:layout_alignParentStart="true"
        android:layout_alignParentLeft="true"
        android:layout_alignParentTop="true"
        android:layout_marginStart="80dp"
        android:layout_marginLeft="80dp"
        android:layout_marginTop="270dp"
        android:background="#11000000"
        android:drawableLeft="@drawable/ic_action_password"
        android:ems="10"
        android:inputType="textPersonName"
        android:text="Mật khẩu"
        android:textSize="20dp" />

    <CheckBox
        android:id="@+id/checkBox"
        android:layout_width="275dp"
        android:layout_height="30dp"
        android:layout_alignParentStart="true"
        android:layout_alignParentLeft="true"
        android:layout_centerVertical="true"
        android:layout_marginStart="80dp"
        android:layout_marginLeft="80dp"
        android:text="Nhớ mật khẩu" />

    <androidx.cardview.widget.CardView
        android:layout_width="275dp"
        android:layout_height="60dp"
        android:layout_alignParentStart="true"
        android:layout_alignParentLeft="true"
        android:layout_alignParentBottom="true"
        android:layout_marginStart="80dp"
        android:layout_marginLeft="80dp"
        android:layout_marginBottom="200dp"
        app:cardBackgroundColor="@android:color/holo_red_dark">

        <RelativeLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent">

            <TextView
                android:id="@+id/textView2"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_centerInParent="true"
                android:text="Đăng nhập"
                android:textColor="#FFFFFF" />
        </RelativeLayout>
    </androidx.cardview.widget.CardView>

    <androidx.cardview.widget.CardView
        android:layout_width="275dp"
        android:layout_height="60dp"
        android:layout_alignParentStart="true"
        android:layout_alignParentLeft="true"
        android:layout_alignParentBottom="true"
        android:layout_marginStart="80dp"
        android:layout_marginLeft="80dp"
        android:layout_marginBottom="130dp"
    app:cardBackgroundColor="#11000000">

        <RelativeLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent">

            <TextView
                android:id="@+id/textView3"
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:text="Tạo tài  khoản"
                android:textColor="#FFFFFF"
                android:layout_centerInParent="true"/>

        </RelativeLayout>
    </androidx.cardview.widget.CardView>

    <Button
        android:id="@+id/button"
        android:layout_width="122dp"
        android:layout_height="wrap_content"
        android:layout_alignParentStart="true"
        android:layout_alignParentLeft="true"
        android:layout_alignParentBottom="true"
        android:layout_marginStart="80dp"
        android:layout_marginLeft="80dp"
        android:layout_marginBottom="70dp"
        android:text="@string/quenmatkhau"
        android:background="#11000000"/>

    <TextView
        android:id="@+id/textView4"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentEnd="true"
        android:layout_alignParentRight="true"
        android:layout_alignParentBottom="true"
        android:layout_marginEnd="85dp"
        android:layout_marginRight="85dp"
        android:layout_marginBottom="0dp"
        android:text="Bạch trung kiên - 1811505310121" />


</>
