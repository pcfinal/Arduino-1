int buttonState = 0;



void setup() {

  // put your setup code here, to run once:

   pinMode(2, INPUT);

   pinMode(4, OUTPUT);

   Serial.begin(9600);

}



void loop() {

  // put your main code here, to run repeatedly:

   buttonState = digitalRead(2);



   if (buttonState == HIGH)

   {

    Serial.println("HIGH");

   }else

   {

    Serial.println("LOW");

   }

   digitalWrite(4, HIGH);



   delay(1000);



   digitalWrite(4, LOW);



   delay(1000);

}
