# Shubhangi_CCA_Mechatronics_2020

## Week 1
- Idea : To make rides from a theme park
- Worked on Carousel and a Cup-ride
# Carousel
- Worm gear used to rotate it
- Threads kept at off center to change the height of the sticks
- ![Carousel](/Week_1/Videos/Carousel.gif)
# Cup-Ride
- Bevel gear used to rotate it
- Height of the flexible arms is changed by the uneven height of the round boundary
- ![Cup-ride](/Week_1/Videos/Cup_Ride.gif)
- ![Cup-ride](/Week_1/Videos/Cup_ride_initial.gif)


## Week 2
- Idea : To introduce gears in the previous made rides
- Worked more on Carousel and gear mechanisms
- # Carousel Improved
- All the mechanism shrinked down and made using wood
- Worm gear removed and normal gears used instead
- ![Carousel New](/Week_2/Videos/Carousel.gif)
# Gears
- I tried different gears for the final thing
- ![Stick&piniongear](/Week_2/Videos/Stick_and_pinion_gear.gif)
- ![Normal gears](/Week_2/Videos/Gears.gif)


## Week 3
- Idea : To improve the gear mechanism and combine all the rides to a single gear so that it can be attached with motor
- Worked more on the gears and their fittings
# Gears
- I combined all the rides together to a single gear so that a motor could be attached
- The problem I faced was a lot of friction, so I'll be working on reducing that in the future
- ![Gear Mechanism](/Week_3/Videos/Gear_mechanism_2.gif)
- ![Theme Park](/Week_3/Images/Theme_Park_2.jpg)


## Week 4
- Idea : To make lights match with a song on Arduino
- Worked on the Arduino board and refined the gear mechanisms
# Gears
- I wanted to reduce the friction, so I shifted the whole mechanism on a plastic sheet
- The motor was finally able to drive the gears 
- ![Motor Gears](/Week_4/Videos/Motor_Theme_Park_gif.gif)

# Arduino
- Made a light blinking setting that would go along with the Hedwig's Theme
- I used the delay command to do this as of now
- The [Youtube Link](https://youtu.be/mXOWHyFg0Co) of the board (turn the sound on)
- Code for the lights :

```CPP
  void setup() {
  pinMode(LED_BUILTIN, OUTPUT);
  pinMode(1, OUTPUT);
  pinMode(2, OUTPUT);
  pinMode(3, OUTPUT);
  pinMode(4, OUTPUT);
  pinMode(5, OUTPUT);
  pinMode(6, OUTPUT);
  pinMode(7, OUTPUT);
  pinMode(8, OUTPUT);
  pinMode(9, OUTPUT);
  pinMode(10, OUTPUT);
  pinMode(11, OUTPUT);
  pinMode(12, OUTPUT);

}


void loop() {
  digitalWrite(1, HIGH);   
  delay(140);                       
  digitalWrite(1, LOW);    
  delay(140); 
  digitalWrite(2, HIGH);   
  delay(320);                       
  digitalWrite(2, LOW);    
  delay(320);     
  digitalWrite(3, HIGH);   
  delay(95);                       
  digitalWrite(3, LOW);    
  delay(95);     
  digitalWrite(4, HIGH);   
  delay(170);                       
  digitalWrite(4, LOW);    
  delay(170);     
  digitalWrite(5, HIGH);   
  delay(295);                       
  digitalWrite(5, LOW);    
  delay(295); 
  digitalWrite(6, HIGH);   
  delay(165);                       
  digitalWrite(6, LOW);    
  delay(165); 
  digitalWrite(7, HIGH);   
  delay(580);                       
  digitalWrite(7, LOW);    
  delay(580);     
  digitalWrite(8, HIGH);   
  delay(520);                       
  digitalWrite(8, LOW);    
  delay(520);     
  digitalWrite(9, HIGH);   
  delay(290);                       
  digitalWrite(9, LOW);    
  delay(290);     
  digitalWrite(10, HIGH);   
  delay(120);                       
  digitalWrite(10, LOW);    
  delay(120);
  digitalWrite(11, HIGH);   
  delay(170);                       
  digitalWrite(11, LOW);    
  delay(240); 
  digitalWrite(12, HIGH);   
  delay(395);                       
  digitalWrite(12, LOW);    
  delay(395);   
  digitalWrite(1, HIGH);   
  delay(125);                       
  digitalWrite(1, LOW);    
  delay(125); 
  digitalWrite(2, HIGH);   
  delay(375);                       
  digitalWrite(2, LOW);    
  delay(375);     
  digitalWrite(3, HIGH);   
  delay(130);                       
  digitalWrite(3, LOW);    
  delay(130);     
  digitalWrite(4, HIGH);   
  delay(480);                       
  digitalWrite(4, LOW);    
  delay(480);     
  digitalWrite(5, HIGH);   
  delay(125);                       
  digitalWrite(5, LOW);    
  delay(125); 
  digitalWrite(6, HIGH);   
  delay(265);                       
  digitalWrite(6, LOW);    
  delay(265); 
  digitalWrite(7, HIGH);   
  delay(110);                       
  digitalWrite(7, LOW);    
  delay(110);     
  digitalWrite(8, HIGH);   
  delay(170);                       
  digitalWrite(8, LOW);    
  delay(170);     
  digitalWrite(9, HIGH);   
  delay(355);                       
  digitalWrite(9, LOW);    
  delay(355);     
  digitalWrite(10, HIGH);   
  delay(140);                       
  digitalWrite(10, LOW);    
  delay(140);
  digitalWrite(11, HIGH);   
  delay(360);                       
  digitalWrite(11, LOW);    
  delay(360); 
  digitalWrite(12, HIGH);   
  delay(180);                       
  digitalWrite(12, LOW);    
  delay(180);   
  digitalWrite(1, HIGH);   
  delay(435);                       
  digitalWrite(1, LOW);    
  delay(435); 
  digitalWrite(2, HIGH);   
  delay(140);                       
  digitalWrite(2, LOW);    
  delay(140);     
  digitalWrite(3, HIGH);   
  delay(265);                       
  digitalWrite(3, LOW);    
  delay(265);     
  digitalWrite(4, HIGH);   
  delay(115);                       
  digitalWrite(4, LOW);    
  delay(115);     
  digitalWrite(5, HIGH);   
  delay(150);                       
  digitalWrite(5, LOW);    
  delay(150); 
  digitalWrite(6, HIGH);   
  delay(385);                       
  digitalWrite(6, LOW);    
  delay(385); 
  digitalWrite(7, HIGH);   
  delay(175);                       
  digitalWrite(7, LOW);    
  delay(175);     
  digitalWrite(8, HIGH);   
  delay(390);                       
  digitalWrite(8, LOW);    
  delay(390);     
  digitalWrite(9, HIGH);   
  delay(240);                       
  digitalWrite(9, LOW);    
  delay(240);     
  digitalWrite(10, HIGH);   
  delay(335);                       
  digitalWrite(10, LOW);    
  delay(335);
  digitalWrite(11, HIGH);   
  delay(1000);                       
  digitalWrite(11, LOW);    
  delay(1000); 
  digitalWrite(12, HIGH);   
  delay(1000);                       
  digitalWrite(12, LOW);    
  delay(1000);     
 
                                                   
}
```

## Pre-midsem week
- I worked on the theme park a little more, and wanted to make a roller coaster ride based on a line following bot idea
- I had to move back to India, and left a lot of my things in the college itself, so I started working just on the line following bot
- I had to scavenge a lot of parts to make the bot to work (could not buy them because of the lockdown)
- The IR sensor emitter pair I had were faulty so I had to try and test another IR led to see if it worked
- I was able to find IR Led in old remote controls that I broke to use it
 ![IRLED](/Pre_midsem_Week/Finding_IRLED.jpg)


- The resistor value I was using was very less, and I needed a 10k ohm resistor for it to work properly
- I broke a few charger adapters to find these resistors, arranged them in series to get a good value
![IRLED](/Pre_midsem_Week/Breaking_Adapters.jpg)
![IRLED](/Pre_midsem_Week/Breaking_Adapters_2.jpg)

- I only haad one transistor, but I needed two to control the motors
- I was able to find transistors on the circuit board of the remote control I broke earlier
- I also tried using scavenged wires to try and connect a transistor that did not have proper legs
![IRLED](/Pre_midsem_Week/Circuits_found.jpg)
![IRLED](/Pre_midsem_Week/Scavenging wire.jpg)

- The bot was working now, but there was a lot of friction so I needed one more tire at the front
- I took the tire out of an old fruit trolley (with the help of my father) and oiled it to make it work without friction
![IRLED](/Pre_midsem_Week/All_direction_tire_from_a_fruit_trolley.jpg)
![IRLED](/Pre_midsem_Week/Oiling_the_tire.jpg)


## Midsem Week
- Combined all the parts together and made the bot to work
- Tried two different codes to make the bot work
- The [Youtube Link](https://youtu.be/a-yLbLEQiu8) of my bot
- The [Youtube Link](https://youtu.be/ZgBRjx-Byh4) of how it works
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

## Week 7
- Idea 1 : To make a paper aeroplane maker and thrower bot
- Idea 2 : To make a quadcopter that delivers things
# Quadcopter mechanism
- https://www.youtube.com/watch?v=6KC-a97joew
# Paper aeroplane machine
- (https://www.youtube.com/watch?v=iHmCseRFV2M&t=16s)
- https://www.youtube.com/watch?v=brQMq8Vz4QA&t=70s (same machine made using lego!)

## Week 8
- Started building the mechanism of the paper aeroplane folding machine
- Mechanism of the first fold
- ![First Fold](/Week_8/FirstFold.jpg)
- ![First Fold 2](/Week_8/FirstFoldMechanism.gif)

## Week 9
- Initial mechanism of second fold
-![Second Fold](/Week_9/SecondFold.gif)

## Week 10
- Final video of the project (https://youtu.be/nOUETtbUJ7E)
- The code for this is was very simple, and mostly involved mechnism. The same code was used, by changing the angles for each step.
 
 ```CPP
 #include <Servo.h>

Servo myservo;  

int pos = 0;    
void setup() {
  myservo.attach(9);  
  for (pos = 60; pos <= 180; pos += 1) { 
    myservo.write(pos);              /
    delay(15);                       
  delay(1000);
  for (pos = 180; pos >= 60; pos -= 1) { 
    myservo.write(pos);            
    delay(15);                      
  }
  
}

void loop() 
{
//empty
}
```



