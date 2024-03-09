# Ex.No:3a Develop program to create a text field and a button “Navigate”. When you enter “www.gmail.com” and press navigate button it should open google page using Implicit Intents.


## AIM:

To create a navigate button using Implicit Intent to display the gmail page using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:

Step 1:
Open Android Stdio and then click on File -> New -> New project.

Step 2:
Then type the Application name as “ex.no.2″ and click Next.

Step 3:
Then select the Minimum SDK as shown below and click Next.

Step 4:
Then select the Empty Activity and click Next. Finally click Finish.

Step 5:
Design layout in activity_main.xml.

Step 6:
Open google page using Implicit Intents and display factorial number using Explicit Intents in MainActivity file.

Step 7:
Save and run the application.
## PROGRAM:
```
/*
Program to print the text “Implicitintent”.
Developed by: SELVAMUTHU KUMARAN V
Registeration Number : 212222040151
*/
```
## MAIN ACTIVITY JAVA
```
package com.example.steve;
import androidx.appcompat.app.AppCompatActivity;
import android.os.Bundle;
import android.widget.Toast;
public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast toast = Toast.makeText(getApplicationContext(), "onCreate Called", Toast.LENGTH_LONG);
        toast.show();

    }

    @Override
    protected void onRestart() {
        super.onRestart();
        Toast toast = Toast.makeText(getApplicationContext(), "onRestart Called", Toast.LENGTH_LONG);
        toast.show();
    }

    @Override
    protected void onStart() {
        super.onStart();
        Toast toast = Toast.makeText(getApplicationContext(), "onstart Called", Toast.LENGTH_LONG);
        toast.show();

    }

    @Override
    protected void onPause() {
        super.onPause();
        Toast toast = Toast.makeText(getApplicationContext(), "onPause Called", Toast.LENGTH_LONG);
        toast.show();
    }

    @Override
    protected void onStop(){
        super.onStop();
        Toast toast = Toast.makeText(getApplicationContext(), "OnStop called", Toast.LENGTH_LONG);
        toast.show();
    }

    @Override
    protected void onDestroy(){
        super.onDestroy();
        Toast toast = Toast.makeText(getApplicationContext(), "OnDestroy called", Toast.LENGTH_LONG);
        toast.show();
    }

}

```
## XML
```
<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools">

    <application
        android:allowBackup="true"
        android:dataExtractionRules="@xml/data_extraction_rules"
        android:fullBackupContent="@xml/backup_rules"
        android:icon="@drawable/ic_launcher_foreground"
        android:label="@string/app_name"
        android:roundIcon="@mipmap/ic_launcher_round"
        android:supportsRtl="true"
        android:theme="@style/Theme.Steve"
        tools:targetApi="31">
        <activity
            android:name=".MainActivity"
            android:exported="true">
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />

                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
    </application>

</manifest>
```
## OUTPUT

![Screenshot (60)](https://github.com/selva258963/ImplicitIntent-MAD/assets/121961701/8c94f8d9-f865-46fe-a6c9-0800abf856d6)
![Screenshot (61)](https://github.com/selva258963/ImplicitIntent-MAD/assets/121961701/c4439767-01b0-4108-91f7-9f693c88ca31)
![Screenshot (62)](https://github.com/selva258963/ImplicitIntent-MAD/assets/121961701/14fd522c-1adf-40cb-8bd8-a54be4712f29)
![Screenshot (63)](https://github.com/selva258963/ImplicitIntent-MAD/assets/121961701/d988c5d7-c2ad-44a0-a00f-17fff9b2b003)



## RESULT
Thus a Simple Android Application create a navigate button using Implicit Intent to display the gmail page using Android Studio is developed and executed successfully.


