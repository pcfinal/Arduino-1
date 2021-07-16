switch:

int button_pressed = 3;



void setup() {

  // put your setup code here, to run once:

   Serial.begin(9600);



   switch (button_pressed) {

    case 1:

       Serial.println("button 1 pressed");

       break;

       case 2:

       Serial.println("button 2 pressed");

       break;

       default:

       Serial.println("i don't know which button was pressed");

       break;

   }

}



void loop() {

  // put your main code here, to run repeatedly:



}
