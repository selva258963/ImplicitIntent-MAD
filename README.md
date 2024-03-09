# Ex.No:3a Develop program to create a text field and a button “Navigate”. When you enter “www.gmail.com” and press navigate button it should open google page using Implicit Intents.
## AIM:
To create a navigate button using Implicit Intent to display the gmail page using Android Studio.
## EQUIPMENTS REQUIRED:
Latest Version Android Studio
## ALGORITHM:
Step 1:Open Android Stdio and then click on File -> New -> New project.
Step 2:Then type the Application name as “ex.no.2″ and click Next.
Step 3:Then select the Minimum SDK as shown below and click Next.
Step 4:Then select the Empty Activity and click Next. Finally click Finish.
Step 5:Design layout in activity_main.xml.
Step 6:Open google page using Implicit Intents and display factorial number using Explicit Intents in MainActivity file.
Step 7:Save and run the application.
## PROGRAM:
```
/*
Program to print the text “Implicitintent”.
Developed by:
Registeration Number :
*/
```
## XML:
```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/textView2"
        android:layout_width="403dp"
        android:layout_height="159dp"
        android:text="IMPLICIT INTENT"
        android:textAlignment="center"
        android:textColorHighlight="#FFFFFF"
        android:textDirection="locale"
        android:textSelectHandle="@android:drawable/alert_dark_frame"
        android:textSize="34sp"
        app:layout_constraintBottom_toTopOf="@+id/editTextText"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.033" />

    <Button
        android:id="@+id/button"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginBottom="80dp"
        android:rotationY="-4"
        android:text="CLICK ME"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent" />

    <EditText
        android:id="@+id/editTextText"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginBottom="180dp"
        android:ems="10"
        android:inputType="text"
        android:text=" "
        app:layout_constraintBottom_toTopOf="@+id/button"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.542"
        app:layout_constraintStart_toStartOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>
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
## OUTPUT
![Screenshot (60)](https://github.com/suryacse05/ImplicitIntent-MAD/assets/121961701/a54e64fe-beba-4650-923e-857634ebfce6)
![Screenshot (61)](https://github.com/suryacse05/ImplicitIntent-MAD/assets/121961701/2cf3cb66-e2cb-4ce3-b6ae-a1dd6b1bf977)
![Screenshot (62)](https://github.com/suryacse05/ImplicitIntent-MAD/assets/121961701/ecf09b82-9bd5-4d1a-8391-4df67b1489e9)
![Screenshot (63)](https://github.com/suryacse05/ImplicitIntent-MAD/assets/121961701/de80eb00-7d51-489e-976a-9a27a4b2e7e6)
## RESULT
Thus a Simple Android Application create a navigate button using Implicit Intent to display the gmail page using Android Studio is developed and executed successfully.


