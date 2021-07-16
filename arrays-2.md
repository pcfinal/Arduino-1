int my_integers[6] = {1,

                      2,

                      3,

                      4,

                      5

                      };



void setup() {

  // put your setup code here, to run once:

   Serial.begin(9600);



   while(!Serial)

   {

    ;

   }



   Serial.println("Your array numbers:");



   for (int ali = 0; ali < 5; ali++)

   {

    Serial.print("ali");

    Serial.print(ali);

    Serial.print(" contains value ");

    Serial.println(my_integers[ali]);

   }

}

void loop() {

  // put your main code here, to run repeatedly:
