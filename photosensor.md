   // photosensor: basic read values on serial monitor



void setup() {

  // put your setup code here, to run once:

   Serial.begin(9600);

}



void loop() {

  // put your main code here, to run repeatedly:

   int sensorValue = analogRead(A5);

   Serial.println(sensorValue);

   delay(10);

}
