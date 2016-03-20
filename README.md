# let-s-do-it-Layout


<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingBottom="@dimen/activity_vertical_margin"
    android:paddingLeft="@dimen/activity_horizontal_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    tools:context="com.example.yuki.letsdoit.MainActivity">

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="New Text"
        android:id="@+id/QuestionTextView"
        android:layout_alignParentTop="true"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true" />

    <EditText
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:id="@+id/AnswerText"
        android:layout_below="@+id/QuestionTextView"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true" />

    <Button
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Check Answer"
        android:id="@+id/AnswerButton"
        android:layout_below="@+id/AnswerText"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true"
        android:background="#8cd8c8" />

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="New Text"
        android:id="@+id/AnswerTextView"
        android:layout_below="@+id/AnswerButton"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true" />

    <Button
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Show Next Question"
        android:id="@+id/QuestionButton"
        android:layout_below="@+id/AnswerTextView"
        android:layout_alignParentLeft="true"
        android:layout_alignParentStart="true"
        android:background="#8cd8c8" />

</RelativeLayout>
