# MAD_Anket_Odev






<!--activity_main-->
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#343e45"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="177dp"
        android:layout_marginTop="20dp"
        android:layout_marginEnd="176dp"
        android:layout_marginBottom="20dp"
        android:text="SORU 1"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/textView2"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <TextView
        android:id="@+id/textView2"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:layout_marginStart="40dp"
        android:layout_marginEnd="50dp"
        android:layout_marginBottom="20dp"
        android:text="Aşağıdaki sanatçılardan hangilerini duydunuz?"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/checkBox"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent" />

    <CheckBox
        android:id="@+id/checkBox"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="40dp"
        android:layout_marginEnd="275dp"
        android:layout_marginBottom="40dp"
        android:text="Ceza"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/checkBox2"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent" />

    <CheckBox
        android:id="@+id/checkBox2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="40dp"
        android:layout_marginEnd="275dp"
        android:layout_marginBottom="40dp"
        android:text="Defkhan"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/checkBox3"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent" />

    <CheckBox
        android:id="@+id/checkBox3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="40dp"
        android:layout_marginEnd="275dp"
        android:layout_marginBottom="40dp"
        android:text="Edis"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/checkBox4"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent" />

    <CheckBox
        android:id="@+id/checkBox4"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="40dp"
        android:layout_marginEnd="275dp"
        android:layout_marginBottom="40dp"
        android:text="Ben Fero"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/checkBox5"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent" />

    <CheckBox
        android:id="@+id/checkBox5"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="40dp"
        android:layout_marginEnd="275dp"
        android:layout_marginBottom="60dp"
        android:text="Skillet"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/button"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent" />

    <Button
        android:id="@+id/button"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginLeft="145dp"
        android:layout_marginRight="145dp"
        android:layout_marginBottom="55dp"
        android:text="Devam"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>

<!--activity_main2-->
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#343e45"
    tools:context=".MainActivity2">


    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="177dp"
        android:layout_marginTop="20dp"
        android:layout_marginEnd="176dp"
        android:layout_marginBottom="20dp"
        android:text="SORU 2"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/textView2"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <TextView
        android:id="@+id/textView2"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:layout_marginStart="40dp"
        android:layout_marginEnd="50dp"
        android:layout_marginBottom="20dp"
        android:text="Aşağıdaki şehirlerden hangilerini gördünüz?"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/checkBox"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent" />

    <CheckBox
        android:id="@+id/checkBox"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="40dp"
        android:layout_marginEnd="275dp"
        android:layout_marginBottom="40dp"
        android:text="İstanbul"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/checkBox2"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent" />

    <CheckBox
        android:id="@+id/checkBox2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="40dp"
        android:layout_marginEnd="275dp"
        android:layout_marginBottom="40dp"
        android:text="Ankara"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/checkBox3"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent" />

    <CheckBox
        android:id="@+id/checkBox3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="40dp"
        android:layout_marginEnd="275dp"
        android:layout_marginBottom="40dp"
        android:text="İzmir"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/checkBox4"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent" />

    <CheckBox
        android:id="@+id/checkBox4"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="40dp"
        android:layout_marginEnd="275dp"
        android:layout_marginBottom="40dp"
        android:text="Bursa"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/checkBox5"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent" />

    <CheckBox
        android:id="@+id/checkBox5"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="40dp"
        android:layout_marginEnd="275dp"
        android:layout_marginBottom="60dp"
        android:text="Muğla"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/button"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent" />

    <Button
        android:id="@+id/button"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginLeft="145dp"
        android:layout_marginRight="145dp"
        android:layout_marginBottom="55dp"
        android:text="Devam"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent" />

    </androidx.constraintlayout.widget.ConstraintLayout>
    
    

  <!--activity_main3-->
  
  <?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#343e45"
    tools:context=".MainActivity3">

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="177dp"
        android:layout_marginTop="20dp"
        android:layout_marginEnd="176dp"
        android:layout_marginBottom="20dp"
        android:text="SORU 3"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/textView2"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <TextView
        android:id="@+id/textView2"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:layout_marginStart="40dp"
        android:layout_marginEnd="50dp"
        android:layout_marginBottom="20dp"
        android:text="Aşağıdaki oyun serilerinden hangilerini oynadınız? (en az 1 oyunu)"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/checkBox"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent" />

    <CheckBox
        android:id="@+id/checkBox"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="40dp"
        android:layout_marginEnd="275dp"
        android:layout_marginBottom="40dp"
        android:text="Mount and Blade"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/checkBox2"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent" />

    <CheckBox
        android:id="@+id/checkBox2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="40dp"
        android:layout_marginEnd="275dp"
        android:layout_marginBottom="40dp"
        android:text="Counter-Strike"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/checkBox3"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent" />

    <CheckBox
        android:id="@+id/checkBox3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="40dp"
        android:layout_marginEnd="275dp"
        android:layout_marginBottom="40dp"
        android:text="God of War"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/checkBox4"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent" />

    <CheckBox
        android:id="@+id/checkBox4"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="40dp"
        android:layout_marginEnd="275dp"
        android:layout_marginBottom="40dp"
        android:text="Cyberpunk"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/checkBox5"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent" />

    <CheckBox
        android:id="@+id/checkBox5"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="40dp"
        android:layout_marginEnd="275dp"
        android:layout_marginBottom="60dp"
        android:text="The Witcher"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/button"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent" />

    <Button
        android:id="@+id/button"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginLeft="145dp"
        android:layout_marginRight="145dp"
        android:layout_marginBottom="55dp"
        android:text="Devam"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>

<!--activity_main4-->
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#343e45"
    tools:context=".MainActivity4">


    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="177dp"
        android:layout_marginTop="20dp"
        android:layout_marginEnd="176dp"
        android:layout_marginBottom="20dp"
        android:text="SORU 4"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/textView2"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.0" />

    <TextView
        android:id="@+id/textView2"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:layout_marginStart="40dp"
        android:layout_marginEnd="50dp"
        android:layout_marginBottom="4dp"
        android:text="Aralarındaki yaş farkı 8 olan iki kişinin 10 yıl sonraki yaş farkı kaç yıl olur?"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/radioGroup"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toStartOf="parent" />

    <Button
        android:id="@+id/button"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginLeft="145dp"
        android:layout_marginRight="145dp"
        android:layout_marginBottom="55dp"
        android:text="Devam"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent" />

    <RadioGroup
        android:id="@+id/radioGroup"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="40dp"
        android:layout_marginEnd="175dp"
        android:layout_marginBottom="50dp"
        android:textColor="@color/white"
        app:layout_constraintBottom_toTopOf="@+id/button"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.692"
        app:layout_constraintStart_toStartOf="parent">

        <RadioButton
            android:id="@+id/radioButton"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginBottom="40dp"
            android:text="4"
            android:textColor="@color/white"
            android:textSize="20dp"
            android:textStyle="bold" />

        <RadioButton
            android:id="@+id/radioButton2"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginBottom="40dp"
            android:text="8"
            android:textColor="@color/white"
            android:textSize="20dp"
            android:textStyle="bold" />

        <RadioButton
            android:id="@+id/radioButton3"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginBottom="40dp"
            android:text="12"
            android:textColor="@color/white"
            android:textSize="20dp"
            android:textStyle="bold" />

        <RadioButton
            android:id="@+id/radioButton4"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginBottom="40dp"
            android:text="16"
            android:textColor="@color/white"
            android:textSize="20dp"
            android:textStyle="bold" />

        <RadioButton
            android:id="@+id/radioButton5"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginBottom="40dp"
            android:text="20"
            android:textColor="@color/white"
            android:textSize="20dp"
            android:textStyle="bold" />

    </RadioGroup>

</androidx.constraintlayout.widget.ConstraintLayout>





  <!--activity_main5-->
  <?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#343e45"
    tools:context=".MainActivity5">

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="177dp"
        android:layout_marginTop="20dp"
        android:layout_marginEnd="176dp"
        android:layout_marginBottom="20dp"
        android:text="SORU 5"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/textView2"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.0"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.0" />

    <TextView
        android:id="@+id/textView2"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:layout_marginStart="40dp"
        android:layout_marginEnd="50dp"
        android:layout_marginBottom="28dp"
        android:text="Almanya'nın başkenti neresidir?"
        android:textColor="@color/white"
        android:textSize="20dp"
        android:textStyle="bold"
        app:layout_constraintBottom_toTopOf="@+id/radioGroup"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="1.0"
        app:layout_constraintStart_toStartOf="parent" />

    <Button
        android:id="@+id/button"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginLeft="145dp"
        android:layout_marginRight="145dp"
        android:layout_marginBottom="55dp"
        android:text="Gönder"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent" />

    <RadioGroup
        android:id="@+id/radioGroup"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="40dp"
        android:layout_marginEnd="175dp"
        android:layout_marginBottom="50dp"
        android:textColor="@color/white"
        app:layout_constraintBottom_toTopOf="@+id/button"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.634"
        app:layout_constraintStart_toStartOf="parent">

        <RadioButton
            android:id="@+id/radioButton"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginBottom="40dp"
            android:text="Köln"
            android:textColor="@color/white"
            android:textSize="20dp"
            android:textStyle="bold" />

        <RadioButton
            android:id="@+id/radioButton2"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginBottom="40dp"
            android:text="Frankfurt"
            android:textColor="@color/white"
            android:textSize="20dp"
            android:textStyle="bold" />

        <RadioButton
            android:id="@+id/radioButton3"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginBottom="40dp"
            android:text="Dresden"
            android:textColor="@color/white"
            android:textSize="20dp"
            android:textStyle="bold" />

        <RadioButton
            android:id="@+id/radioButton4"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginBottom="40dp"
            android:text="Berlin"
            android:textColor="@color/white"
            android:textSize="20dp"
            android:textStyle="bold" />

        <RadioButton
            android:id="@+id/radioButton5"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginBottom="40dp"
            android:text="Münih"
            android:textColor="@color/white"
            android:textSize="20dp"
            android:textStyle="bold" />

    </RadioGroup>

</androidx.constraintlayout.widget.ConstraintLayout>






// MainActivity
package com.example.anketodev;

import androidx.appcompat.app.AppCompatActivity;

import android.content.Intent;
import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import android.widget.CheckBox;

public class MainActivity extends AppCompatActivity {
    private CheckBox chc1,chc2,chc3,chc4, chc5;
    private Button btnDevam;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        chc1 = findViewById(R.id.checkBox);
        chc2 = findViewById(R.id.checkBox2);
        chc3 = findViewById(R.id.checkBox3);
        chc4 = findViewById(R.id.checkBox4);
        chc5 = findViewById(R.id.checkBox5);

        btnDevam = findViewById(R.id.button);
        btnDevam.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                Intent devamEt = new Intent(MainActivity.this,MainActivity2.class);
                startActivity(devamEt);
            }
        });

    }

}

// MainActivity2
package com.example.anketodev;

import androidx.appcompat.app.AppCompatActivity;

import android.content.Intent;
import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import android.widget.CheckBox;

public class MainActivity2 extends AppCompatActivity {
    private Button btnDevam;
    private CheckBox chc1,chc2,chc3,chc4,chc5;


    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main2);
        chc1 = findViewById(R.id.checkBox);
        chc2 = findViewById(R.id.checkBox2);
        chc3 = findViewById(R.id.checkBox3);
        chc4 = findViewById(R.id.checkBox4);
        chc5 = findViewById(R.id.checkBox5);

        btnDevam = findViewById(R.id.button);
        btnDevam.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                Intent devamEt = new Intent(MainActivity2.this,MainActivity3.class);
                startActivity(devamEt);
            }
        });

    }
}

// MainActivity3
package com.example.anketodev;

import androidx.appcompat.app.AppCompatActivity;

import android.content.Intent;
import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import android.widget.CheckBox;

public class MainActivity3 extends AppCompatActivity {
    private Button btnDevam;
    private CheckBox chc1,chc2,chc3,chc4,chc5;


    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main3);
        chc1 = findViewById(R.id.checkBox);
        chc2 = findViewById(R.id.checkBox2);
        chc3 = findViewById(R.id.checkBox3);
        chc4 = findViewById(R.id.checkBox4);
        chc5 = findViewById(R.id.checkBox5);

        btnDevam = findViewById(R.id.button);
        btnDevam.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                Intent devamEt = new Intent(MainActivity3.this,MainActivity4.class);
                startActivity(devamEt);
            }
        });
    }
}

// MainActivity4
package com.example.anketodev;

import androidx.appcompat.app.AppCompatActivity;

import android.content.Intent;
import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import android.widget.RadioButton;

public class MainActivity4 extends AppCompatActivity {
    private Button btnDevam;
    private RadioButton rdBtn1,rdBtn2,rdBtn3,rdBtn4, rdbtn5;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main4);

        rdBtn1 = findViewById(R.id.radioButton);
        rdBtn2 = findViewById(R.id.radioButton2);
        rdBtn3 = findViewById(R.id.radioButton3);
        rdBtn4 = findViewById(R.id.radioButton4);
        rdbtn5 = findViewById(R.id.radioButton5);

        btnDevam = findViewById(R.id.button);
        btnDevam.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                Intent devamEt = new Intent(MainActivity4.this,MainActivity5.class);
                startActivity(devamEt);
            }
        });
    }
}

// MainActivity5
package com.example.anketodev;

import androidx.appcompat.app.AppCompatActivity;

import android.content.Intent;
import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import android.widget.RadioButton;
import android.widget.Toast;

public class MainActivity5 extends AppCompatActivity {
    private Button btnGonder;
    private RadioButton rdBtn1,rdBtn2,rdBtn3,rdBtn4, rdbtn5;

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main5);


        rdBtn1 = findViewById(R.id.radioButton);
        rdBtn2 = findViewById(R.id.radioButton2);
        rdBtn3 = findViewById(R.id.radioButton3);
        rdBtn4 = findViewById(R.id.radioButton4);
        rdbtn5 = findViewById(R.id.radioButton5);

        btnGonder = findViewById(R.id.button);
        btnGonder.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                Toast.makeText(MainActivity5.this,"Yanıtlarınız gönderildi.",Toast.LENGTH_SHORT).show();
            }
        });
    }
}
