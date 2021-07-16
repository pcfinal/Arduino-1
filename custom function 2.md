void setup() {

   // put your setup code here, to run once:

Serial.begins(9600);

Serial.println("hello");

Serial.println("hello again");

}



void loop() {

   // put your main code here, to run repeatedly:

Serial.println(millis());

delay(1000);

}
