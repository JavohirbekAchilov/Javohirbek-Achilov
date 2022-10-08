- 👋 Hi, I’m @JavohirbekAchilov
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
JavohirbekAchilov/JavohirbekAchilov is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#ffffff"
    tools:context="hs.ws.no.calculator.MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />
    <LinearLayout
        android:id="@+id/linearLayout"
        android:layout_width="match_parent"
        android:layout_height="125dp"
        android:layout_alignParentTop="true"
        android:layout_centerHorizontal="true"
        android:orientation="vertical">

</android.support.constraint.ConstraintLayout>
        <TextView
            android:id="@+id/textView4"
            android:layout_width="match_parent"
            android:layout_height="125dp"
            android:layout_alignParentStart="true"
            android:layout_alignParentTop="true"
            android:background="@color/colorBlue"
            android:paddingLeft="20dp"
            android:paddingRight="20dp"
            android:paddingTop="30dp"
            android:text="0"
            android:textAlignment="textEnd"
            android:textColor="#ffffff"
            android:textSize="50sp" />

    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_marginRight="100dp"
        android:layout_marginTop="125dp"
        android:orientation="vertical">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0dp"
            android:layout_weight="1"
            android:orientation="horizontal">

            <Button
                android:id="@+id/button2"
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:background="@android:color/transparent"
                android:text="7"
                android:textSize="30sp" />

            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:background="@android:color/transparent"
                android:text="8"
                android:textSize="30sp" />

            <Button
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:background="@android:color/transparent"
                android:text="9"
                android:textSize="30sp" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0dip"
            android:layout_weight="1"
            android:background="@android:color/transparent"
            android:orientation="horizontal">

            <Button
                android:id="@+id/button3"
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:background="@android:color/transparent"
                android:text="4"
                android:textSize="30sp" />

            <Button
                android:id="@+id/button4"
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:background="@android:color/transparent"
                android:text="5"
                android:textSize="30sp" />

            <Button
                android:id="@+id/button5"
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:background="@android:color/transparent"
                android:text="6"
                android:textSize="30sp" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0dip"
            android:layout_weight="1"
            android:background="@android:color/transparent"
            android:orientation="horizontal">

            <Button
                android:id="@+id/button6"
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:background="@android:color/transparent"
                android:text="1"
                android:textSize="30sp" />

            <Button
                android:id="@+id/button7"
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:background="@android:color/transparent"
                android:text="2"
                android:textSize="30sp" />

            <Button
                android:id="@+id/button8"
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:background="@android:color/transparent"
                android:text="3"
                android:textSize="30sp" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0dip"
            android:layout_weight="1"
            android:background="@android:color/transparent"
            android:orientation="horizontal">

            <Button
                android:id="@+id/button9"
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:background="@android:color/transparent"
                android:text="0"
                android:textSize="30sp" />

            <Button
                android:id="@+id/button11"
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:background="@android:color/transparent"
                android:text=","
                android:textSize="30sp" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="0dip"
            android:layout_weight="1"
            android:background="@android:color/transparent"
            android:orientation="horizontal">

            <Button
                android:id="@+id/button12"
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="2"
                android:background="@color/colorAccent"
                android:text="Clear"
                android:textColor="#ffffff"
                android:textSize="25sp" />

        </LinearLayout>
    </LinearLayout>

    <LinearLayout
        android:layout_width="100dp"
        android:layout_height="match_parent"
        android:layout_alignParentEnd="true"
        android:layout_below="@+id/linearLayout"
        android:addStatesFromChildren="false"
        android:clipChildren="false"
        android:measureWithLargestChild="false"
        android:orientation="vertical"
        tools:background="@color/colorBlue">

        <ImageButton
            android:id="@+id/imageButton"
            android:layout_width="match_parent"
            android:layout_height="0dp"
            android:layout_weight="1"
            android:backgroundTint="@android:color/transparent"
            app:srcCompat="@drawable/divide" />

        <ImageButton
            android:id="@+id/imageButton2"
            android:layout_width="match_parent"
            android:layout_height="0dip"
            android:layout_weight="1"
            android:backgroundTint="@android:color/transparent"
            app:srcCompat="@drawable/multiply" />

        <ImageButton
            android:id="@+id/imageButton3"
            android:layout_width="match_parent"
            android:layout_height="0dip"
            android:layout_weight="1"
            android:backgroundTint="@android:color/transparent"
            app:srcCompat="@drawable/subtract" />

        <ImageButton
            android:id="@+id/imageButton4"
            android:layout_width="match_parent"
            android:layout_height="0dip"
            android:layout_weight="1"
            android:backgroundTint="@android:color/transparent"
            app:srcCompat="@drawable/add" />

        <ImageButton
            android:id="@+id/imageButton6"
            android:layout_width="match_parent"
            android:layout_height="0dip"
            android:layout_weight="1"
            android:backgroundTint="@android:color/transparent"
            android:padding="28dp"
            android:scaleType="fitCenter"
            app:srcCompat="@drawable/equal" />

    </LinearLayout>
</RelativeLayout>
