# Arduino

Program1
--------
# LED glow
void setup(){
  pinMode(13, OUTPUT);
}
void loop(){
  displayWrite(13,HIGH);
  delay(30000);
  displayWite(13,LOW);
  delay(30000);
}
