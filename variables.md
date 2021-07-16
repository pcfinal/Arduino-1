using variables instead of static numbers (10,11):

void setup() {

// put your setup code here, to run once:

Serial.begin(9600);

Serial.println("simple calculation");

int number_x = 10;

int number_y;

number_y = 11;

Serial.println(ali_calculate(number_x, number_y));

}



void loop() {

// put your main code here, to run repeatedly:

}



int ali_calculate(int number_x, int number_y){

int result = number_x + number_y;

return result ;

}
