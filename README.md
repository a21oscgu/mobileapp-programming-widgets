<i>**OBS! En del commits har råkat bli pushade med mitt personliga konto "drag0nsbreath" istället för mitt skolkonto "a21oscgu".**</i>

# Assignment 3: Layouts & Views

**Den här appen är forkad från LenaSYS/mobileapp-programming-widgets. Appen har en constraint layout. I appen har tre widgets lagts till. Det finns alltså en TextView, en ImageView, en EditText och en Button. Alla widgets har placerats m.h.a. margins och utseendet har även ändrats, se skärmklipp nedanför. Ifall knappen trycks in kommer meddelandet "We clicked on the button!" upp i konsolen. Appens Appbar har även fått en annan färg (jag är medveten om att det inte är helt anpassat efter material design). Den ImageView som skapades syns även i skärmklippet nedanför.**

**Denna kodsnutt visar den ImageView som har skapats:**

```
<ImageView
        android:id="@+id/imageViewKiwi"
        android:layout_width="300dp"
        android:layout_height="300dp"
        android:layout_marginBottom="185dp"
        android:contentDescription="@string/my_kiwi"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:srcCompat="@drawable/kiwi" />
```

**Detta skärmklipp visar layouten i appen:**

<img src="/Screenshot_20220414_150751.png" width="60%">

**Värt att notera, ifall du öppnar filen **<i>activity_main.xml</i>** kanske du märker att det finns ett problem i filen **<cite>"Cannot resolve symbol '@drawable/kiwi':35".</cite>** Jag vet inte vad felet är och har inte lyckats lösa det, se sista raden i kodsnutten ovanför.**
