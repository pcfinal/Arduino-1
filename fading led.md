potentiometer_led (digital pwm ~) *use ports with ~



void setup() {

  // put your setup code here, to run once:

   pinMode(6, OUTPUT);

}



void loop() {

  // put your main code here, to run repeatedly:

  // possible 0...1023

  int potvalue = analogRead(A0);



  int mappedvalue = map(potvalue, 0, 1023, 0, 255);

  // possible value 0...255

  analogWrite(6, mappedvalue);

}
