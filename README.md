# TugasPemrogramanMobile

| Nama      | Anggun Rendra |
| ----------- | ----------- |
| NIM     | 312010022       |
| Kelas   | TI.20.D.1    |


### Hasil Membuat Tampilan UI & UX Menggunakan Android Studio

### 1. Ini adalah tampilan Join Now Untuk Login Ke R E N D R A G Y M

![2023-05-24 (1)](https://github.com/AnggunRendra10/TugasPemrogramanMobile/assets/101658076/30fe852d-db0f-48c1-a5f9-124c9884573a)

Dan dibawah ini adalah Source Code dari hasil diatas

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:src="@drawable/gambar1"
        android:id="@+id/gmbr1"
        />
    <TextView
        android:id="@+id/txt_1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@android:id/accessibilityActionContextClick"
        android:layout_centerHorizontal="true"
        android:layout_marginStart="40dp"
        android:layout_marginTop="100dp"
        android:layout_marginEnd="40dp"
        android:layout_marginBottom="40dp"
        android:fontFamily="@font/inter"
        android:text="R E N D R A  G Y M"
        android:textColor="@color/primaryColor"
        android:textSize="35dp" />

    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:src="@drawable/Athletics"
        android:layout_centerHorizontal="true"
        android:layout_below="@id/txt_1"
        />
    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="GROW TOGETHER"
        android:fontFamily="@font/inter"
        android:textColor="@color/primaryColor"
        android:textSize="10dp"
        android:layout_below="@id/gmbr1"
        android:layout_alignParentLeft="true"
        android:layout_marginLeft="20dp"
        android:id="@+id/txt_2"
        />
    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/txt_2"
        android:width="300dp"
        android:text="JOIN NOW"
        android:textColor="@color/secondaryColor"
        android:layout_centerHorizontal="true"
        android:background="@drawable/button_shape"
        android:textSize="14dp"
        android:fontFamily="@font/inter"
        android:id="@+id/img1"


        />


</RelativeLayout>


