# Ex.No:2 To create a HelloWorld Activity using all lifecycles methods to display messages.

## AIM:

To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:

Step 1: Open Android Stdio and then click on File -> New -> New project.

Step 2: Then type the Application name as HelloWorld and click Next. 

Step 3: Then select the Minimum SDK as shown below and click Next.

Step 4: Then select the Empty Activity and click Next. Finally click Finish.

Step 5: Design layout in activity_main.xml.

Step 6: Display message give in MainActivity file.

Step 7: Save and run the application.

## PROGRAM:
```
/*
Program to print the text “Hello World”.
Developed by: Roopak C S
Registeration Number: 212223220088
*/

package com.example.lifecyclemethods;

import android.os.Bundle;
import android.widget.Toast;

import androidx.appcompat.app.AppCompatActivity;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast toast = Toast.makeText(getApplicationContext(), "onCreate Called", Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStart() {
        super.onStart();
        Toast toast = Toast.makeText(getApplicationContext(), "onStart Called", Toast.LENGTH_LONG);
        toast.show();
    }

    @Override
    protected void onRestart() {
        super.onRestart();
        Toast toast = Toast.makeText(getApplicationContext(), "onRestart Called", Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onPause() {
        super.onPause();
        Toast toast = Toast.makeText(getApplicationContext(), "onPause Called", Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onResume() {
        super.onResume();
        Toast toast = Toast.makeText(getApplicationContext(), "onResume Called", Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStop() {
        super.onStop();
        Toast toast = Toast.makeText(getApplicationContext(), "onStop Called", Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onDestroy() {
        super.onDestroy();
        Toast toast = Toast.makeText(getApplicationContext(), "onDestroy Called", Toast.LENGTH_LONG);
        toast.show();
    }

}
```

## OUTPUT

## OnCreate()
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/36421cd9-b180-42ba-a310-f28c08a7047a" />

## OnStart()
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/db47c244-6ad0-4a4b-ad4d-f22c585801a3" />

## OnRestart()
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/87f237f3-d080-4ece-902e-149437354560" />

## Onpause()
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/69d84f6b-058c-4817-9a3b-ac2c8d6545d0" />

## OnResume()
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/0454dee9-2b8c-48f6-964b-45648d1290fd" />



## RESULT
Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
