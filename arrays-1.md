add this to the last skitch to replace index value:



Serial.println();

    Serial.println("storing new values in index" );

for (int maryam = 0; maryam < 4; maryam++)

   {

    Serial.print(my_integers[maryam]);

    Serial.print("+");

    Serial.print(my_integers[maryam+1]);

    Serial.print(" = ");

    int sum = my_integers[maryam] + my_integers [maryam+1];

    my_integers[maryam] = sum;   // this is what stores it

    Serial.print(my_integers[maryam]);

    Serial.print(" -> maryam ");

    Serial.print(maryam);

    Serial.print(" now contains value ");

    Serial.println(my_integers[maryam]);
