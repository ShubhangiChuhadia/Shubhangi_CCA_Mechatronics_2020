# Line following bot
 ![Bot 1](/Midsem_Week/Bot_1.jpg)
 ![Bot 2](/Midsem_Week/Bot_2.jpg)
 ![Bot 3](/Midsem_Week/Bot_3.jpg)
 ![Bot 4](/Midsem_Week/Bot_4.jpg)
- The [Youtube Link](https://youtu.be/a-yLbLEQiu8) of my bot

- Closeups of the circuit
![Bot 4](/Midsem_Week/Arduino.jpg)
![Bot 2](/Midsem_Week/Ciruit.jpg)
![Bot 3](/Midsem_Week/IRSensors.jpg)

- I tried two codes to make the bot work
- The first one worked on the concept of stopping when it sensed the black surface and moved away from the black line

```CPP

//defining leftVal as the value which occurs when black color is sensed
int leftVal = 995;
int rightVal = 980;
int speedval = 120;


void setup() {
 Serial.begin(9600);
 pinMode(9, OUTPUT);
 pinMode(10, OUTPUT); 

}

void loop() {
 int leftfinal = analogRead(A0);
 int rightfinal = analogRead(A1);
// int leftfinal = map(leftsensor, 0, 400, 0, 100);
// int rightfinal = map(rightsensor, 0, 400, 0, 100);
// Serial.println(leftfinal);
// Serial.println(rightfinal);


 //Commands to test the motor
// if (leftfinal <= leftVal)
// {
//  analogWrite(9, speedval);
//  delay(1000);
//  analogWrite(9, 0);
//  delay(1000);
//  //analogWrite(10, HIGH);
// }
// if (rightfinal<=rightVal)
// {
//  analogWrite(10,speedval);
//  delay(1000);
//  analogWrite(10,0);
//  delay(1000);
//  //analogWrite(10, HIGH);
// }



 if ((leftfinal <= leftVal) && (rightfinal <= rightVal))
 {
  analogWrite(9, speedval);
  analogWrite(10, speedval);
 }
 else if ((leftfinal <= leftVal) && (rightfinal > rightVal))
 {
  analogWrite(9, speedval);
  analogWrite(10, 0);
 }
  else if ((rightfinal <= rightVal) && (leftfinal > leftVal))
 {
  analogWrite(10, speedval);
  analogWrite(9, 0);
 }
  else if ((leftfinal >= leftVal) && (rightfinal >= rightVal))
 {
  analogWrite(9, 0);
  analogWrite(10, 0);
 }
 
}
```

- The second code required the base black line to be thicker and works when the sensors are on black, and stops as soon as it sense the white surface

```CPP
//defining leftVal as the value which occurs when black color is sensed
int leftVal = 995;
int rightVal = 980;
int speedval = 70;


void setup() {
 Serial.begin(9600);
 pinMode(9, OUTPUT);
 pinMode(10, OUTPUT); 

}

void loop() {
 int leftfinal = analogRead(A0);
 int rightfinal = analogRead(A1);
// Serial.println(leftfinal);
// Serial.println(rightfinal);



 if ((leftfinal >= leftVal) && (rightfinal >= rightVal))
 {
  analogWrite(9, speedval);
  analogWrite(10, speedval);
 }
 else if ((leftfinal >= leftVal) && (rightfinal < rightVal))
 {
  analogWrite(9, 0);
  analogWrite(10, speedval);
 }
  else if ((rightfinal >= rightVal) && (leftfinal < leftVal))
 {
  analogWrite(10, 0);
  analogWrite(9, speedval);
 }
  else if ((leftfinal <= leftVal) && (rightfinal <= rightVal))
 {
  analogWrite(9, 0);
  analogWrite(10, 0);
 }
 
}
```
Back to [Home](https://github.com/ShubhangiChuhadia/Shubhangi_CCA_Mechatronics_2020)
