void setup() {

// put your setup code here, to run once:

Serial.begin(9600);

Serial.println("simple calculation");

ali_calculate(10,11);

}



void loop() {

// put your main code here, to run repeatedly:

}



int ali_calculate(int number_x, int number_y){

   Serial.println(number_x + number_y);

}
