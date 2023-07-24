# Automated-Toll-Collection-System
Designed using RFID Module and Arduino.


## Code 
`
#include <SPI.h>
#include <MFRC522.h>
#include <OnewireKeypad.h>
#include <Servo.h>
 
#include <LiquidCrystal.h>

LiquidCrystal lcd(7, 6, 5, 4, 3, 2);
//--LiquidCrystal(RS, E, D4, D5, D6, D7)
//#include <LiquidCrystal_I2C.h>
//LiquidCrystal_I2C lcd(0x27, 16, 2); 
 
Servo servo;
int servoPos = 0;
 
#define sensorPin1 A2
#define sensorPin2 A3
#define buzzerPin 3
 
int senVal1 = 0;
int senVal2 = 0;
`

 

