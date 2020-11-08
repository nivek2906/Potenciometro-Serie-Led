# Potenciometro-Serie-Led
int sensorValue = 0;

void setup(){
  pinMode(8,OUTPUT);
  pinMode(9,OUTPUT);
  pinMode(10,OUTPUT);
  pinMode(11,OUTPUT);
  pinMode(12,OUTPUT);
}

void loop(){
  digitalWrite(8,HIGH);
  sensorValue = analogRead(0);
  delay(sensorValue + 50);
  digitalWrite(8, LOW);
  delay(1);

  digitalWrite(9,HIGH);
  sensorValue = analogRead(0);
  delay(sensorValue + 50);
  digitalWrite(9, LOW);
  delay(1);

  digitalWrite(10,HIGH);
  sensorValue = analogRead(0);
  delay(sensorValue + 50);
  digitalWrite(10, LOW);
  delay(1);

  digitalWrite(11,HIGH);
  sensorValue = analogRead(0);
  delay(sensorValue + 50);
  digitalWrite(11, LOW);
  delay(1);

  digitalWrite(12,HIGH);
  sensorValue = analogRead(0);
  delay(sensorValue + 50);
  digitalWrite(12, LOW);
  delay(1); }
