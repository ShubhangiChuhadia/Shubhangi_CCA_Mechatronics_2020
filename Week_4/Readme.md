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


Back to [Home](https://github.com/ShubhangiChuhadia/Shubhangi_CCA_Mechatronics_2020)
