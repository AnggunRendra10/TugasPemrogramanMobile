# TugasPemrogramanMobile

| Nama      | Anggun Rendra |
| ----------- | ----------- |
| NIM     | 312010022       |
| Kelas   | TI.20.D.1    |


### Hasil Membuat Tampilan UI & UX Menggunakan Android Studio

### 1. Ini adalah tampilan Join Now Untuk Login Ke R E N D R A G Y M

![2023-05-24 (3)](https://github.com/AnggunRendra10/TugasPemrogramanMobile/assets/101658076/500d1512-8733-40d7-8409-422516b3c5bf)


### Dibawah ini adalah Source Code dari hasil diatas

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
        android:id="@+id/img1"/>

</RelativeLayout>


### 2. Ini adalah tampilan Login pada aplikasi R E N D R A G Y M

![2023-05-24 (2)](https://github.com/AnggunRendra10/TugasPemrogramanMobile/assets/101658076/eceb394a-3379-4326-9610-462779597777)

### Dibawah ini adalah Source Code dari tampilan Login

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".RegisterActivity">


    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_marginBottom="-28dp"
        android:src="@drawable/union"
        android:id="@+id/union"/>


    <Button
        android:layout_width="30dp"
        android:layout_height="30dp"
        android:background="@drawable/bg_button"
        android:layout_marginLeft="20dp"
        android:layout_marginTop="30dp"
        android:id="@+id/vector"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Welcome Back!"
        android:fontFamily="@font/interbold"
        android:textColor="@color/primaryColor"
        android:textSize="30dp"
        android:layout_below="@id/vector"
        android:layout_marginLeft="20dp"
        android:layout_marginTop="40dp"
        android:id="@+id/welcome"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Enter Your Usernam & Password"
        android:fontFamily="@font/intersemibold"
        android:textColor="@color/textcolor"
        android:textSize="15dp"
        android:layout_below="@+id/welcome"
        android:layout_marginLeft="25dp"
        android:layout_marginTop="40dp"
        android:id="@+id/enteryour"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Username"
        android:fontFamily="@font/interreguler"
        android:textColor="@color/intercolor"
        android:textSize="30dp"
        android:layout_below="@id/enteryour"
        android:layout_marginLeft="40dp"
        android:layout_marginTop="160dp"
        android:id="@+id/username"/>

    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/username"
        android:background="@drawable/line1"
        android:layout_marginLeft="10dp"
        android:layout_marginTop="25dp"
        android:id="@+id/line1"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Password"
        android:fontFamily="@font/interreguler"
        android:textColor="@color/intercolor"
        android:textSize="30dp"
        android:layout_below="@+id/line1"
        android:layout_marginLeft="40dp"
        android:layout_marginTop="70dp"
        android:id="@+id/password"/>

    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/password"
        android:background="@drawable/line1"
        android:layout_marginLeft="10dp"
        android:layout_marginTop="25dp"
        android:id="@+id/lne2"/>

    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/lne2"
        android:width="300dp"
        android:text="Login"
        android:textColor="@color/secondaryColor"
        android:layout_centerHorizontal="true"
        android:background="@drawable/button_shape"
        android:textSize="25dp"
        android:fontFamily="@font/inter"
        android:layout_marginTop="100dp"
        android:id="@+id/login"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Forgotten Password?"
        android:fontFamily="@font/interreguler"
        android:textColor="@color/intercolor"
        android:textSize="20dp"
        android:layout_below="@+id/login"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="20dp"
        android:id="@+id/forgot"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Or Create New Account"
        android:fontFamily="@font/interreguler"
        android:textColor="@color/intercolor"
        android:textSize="20dp"
        android:layout_below="@+id/forgot"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="10dp"
        android:id="@+id/create"/>

</RelativeLayout>

### 3. Ini adalah tampilan Register pada aplikasi R E N D R A G Y M

![2023-05-25 (4)](https://github.com/AnggunRendra10/TugasPemrogramanMobile/assets/101658076/ef2ccb6b-8969-4bb7-a6c3-6982ca2a9217)

### Dibawah ini adalah Source Code dari tampilan Register

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".register">

    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_marginBottom="-28dp"
        android:src="@drawable/pinki"
        android:id="@+id/pinki"/>

    <Button
        android:layout_width="30dp"
        android:layout_height="30dp"
        android:background="@drawable/bg_button"
        android:layout_marginLeft="20dp"
        android:layout_marginTop="30dp"
        android:id="@+id/button"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Create Account"
        android:fontFamily="@font/interbold"
        android:textColor="@color/primaryColor"
        android:textSize="30dp"
        android:layout_below="@+id/button"
        android:layout_marginTop="40dp"
        android:layout_marginLeft="20dp"
        android:id="@+id/account"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Enter Email Id"
        android:fontFamily="@font/interreguler"
        android:textColor="@color/intercolor"
        android:textSize="30dp"
        android:layout_below="@+id/account"
        android:layout_marginLeft="40dp"
        android:layout_marginTop="90dp"
        android:id="@+id/enteremail"/>

    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/enteremail"
        android:background="@drawable/line1"
        android:layout_centerHorizontal="true"
        android:layout_marginLeft="10dp"
        android:layout_marginTop="30dp"
        android:id="@+id/garis"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Create Username"
        android:fontFamily="@font/interreguler"
        android:textColor="@color/intercolor"
        android:textSize="30dp"
        android:layout_below="@+id/garis"
        android:layout_marginLeft="40dp"
        android:layout_marginTop="60dp"
        android:id="@+id/create"/>

    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/create"
        android:background="@drawable/line1"
        android:layout_centerHorizontal="true"
        android:layout_marginLeft="10dp"
        android:layout_marginTop="30dp"
        android:id="@+id/garing"/>

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Create Passward"
        android:fontFamily="@font/interreguler"
        android:textColor="@color/intercolor"
        android:textSize="30dp"
        android:layout_below="@+id/garing"
        android:layout_marginLeft="40dp"
        android:layout_marginTop="60dp"
        android:id="@+id/passward"/>

    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/passward"
        android:background="@drawable/line1"
        android:layout_centerHorizontal="true"
        android:layout_marginLeft="10dp"
        android:layout_marginTop="30dp"
        android:id="@+id/miring"/>

    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@id/miring"
        android:width="300dp"
        android:text="Register"
        android:textColor="@color/secondaryColor"
        android:layout_centerHorizontal="true"
        android:background="@drawable/button_shape"
        android:textSize="25dp"
        android:fontFamily="@font/inter"
        android:layout_marginTop="100dp"
        android:id="@+id/register"/>

</RelativeLayout>
