TIME CONTROL ROBOT FORWARD

void setup() 
{
 pinMode(3,OUTPUT);     //LEFT MOTOR
 pinMode(4,OUTPUT);
 pinMode(5,OUTPUT);     //RIGHT MOTOR 
 pinMode(6,OUTPUT);
}

void loop() 
{//FORWARD
  digitalWrite(3,HIGH);
  digitalWrite(4,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(6,LOW);
  delay(2000);
  
  
  TIME CONTROL ROBOT BACKWARD
  
void setup() 
{
 pinMode(3,OUTPUT);     //LEFT MOTOR
 pinMode(4,OUTPUT);
 pinMode(5,OUTPUT);     //RIGHT MOTOR 
 pinMode(6,OUTPUT);
}

void loop() 
{//FORWARD
  digitalWrite(3,HIGH);
  digitalWrite(4,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(6,LOW);
  delay(2000);
  
//BACKWARD
  digitalWrite(3,LOW);
  digitalWrite(4,HIGH);
  digitalWrite(5,LOW);
  digitalWrite(6,HIGH);
  delay(2000);

}

TIME CONTROL ROBOT AXIAL TURN

void setup() 
{
 pinMode(3,OUTPUT);     //LEFT MOTOR
 pinMode(4,OUTPUT);
 pinMode(5,OUTPUT);     //RIGHT MOTOR 
 pinMode(6,OUTPUT);
}

void loop() 
{//FORWARD
  digitalWrite(3,HIGH);
  digitalWrite(4,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(6,LOW);
  delay(2000);
  
//BACKWARD
  digitalWrite(3,LOW);
  digitalWrite(4,HIGH);
  digitalWrite(5,LOW);
  digitalWrite(6,HIGH);
  delay(2000);

//AXIAL LEFT TURN
  digitalWrite(3,LOW);
  digitalWrite(4,HIGH);
  digitalWrite(5,HIGH);
  digitalWrite(6,LOW);
  delay(1000);

// AXIAL RIGHT TURN 
  digitalWrite(3,HIGH);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,HIGH);
  delay(1000);
 

}

TIME CONTROL ROBOT RADIAL TURN

void setup() 
{
 pinMode(3,OUTPUT);     //LEFT MOTOR
 pinMode(4,OUTPUT);
 pinMode(5,OUTPUT);     //RIGHT MOTOR 
 pinMode(6,OUTPUT);


 
}

void loop() 
{
 //FORWARD
  digitalWrite(3,HIGH);
  digitalWrite(4,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(6,LOW);
  delay(2000);
  
//BACKWARD
  digitalWrite(3,LOW);
  digitalWrite(4,HIGH);
  digitalWrite(5,LOW);
  digitalWrite(6,HIGH);
  delay(2000);

//RADIAL LEFT TURN
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(6,LOW);
  delay(1000);

// RADIAL RIGHT TURN 
  digitalWrite(3,HIGH);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  delay(1000);


}

TIME CONTROL ROBOT- STOP

void setup() 
{
 pinMode(3,OUTPUT);     //LEFT MOTOR
 pinMode(4,OUTPUT);
 pinMode(5,OUTPUT);     //RIGHT MOTOR 
 pinMode(6,OUTPUT);


 
}

void loop() 
{
 //FORWARD
  digitalWrite(3,HIGH);
  digitalWrite(4,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(6,LOW);
  delay(2000);
  
//BACKWARD
  digitalWrite(3,LOW);
  digitalWrite(4,HIGH);
  digitalWrite(5,LOW);
  digitalWrite(6,HIGH);
  delay(2000);

//RADIAL LEFT TURN
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(6,LOW);
  delay(1000);

// RADIAL RIGHT TURN 
  digitalWrite(3,HIGH);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  delay(1000);

//STOP
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  delay(5000);
}

TIME CONTROL ROBOT-PERMANENT STOP

void setup() 
{
 pinMode(3,OUTPUT);     //LEFT MOTOR
 pinMode(4,OUTPUT);
 pinMode(5,OUTPUT);     //RIGHT MOTOR 
 pinMode(6,OUTPUT);

 //FORWARD
  digitalWrite(3,HIGH);
  digitalWrite(4,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(6,LOW);
  delay(2000);
  
//BACKWARD
  digitalWrite(3,LOW);
  digitalWrite(4,HIGH);
  digitalWrite(5,LOW);
  digitalWrite(6,HIGH);
  delay(2000);

//RADIAL LEFT TURN
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(6,LOW);
  delay(1000);

// RADIAL RIGHT TURN 
  digitalWrite(3,HIGH);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  delay(1000);

//STOP
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  delay(5000);
 
}

void loop() 
{

}
