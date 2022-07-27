# 3rd-Week-task-Electronics
# Analog sensor code
void setup()
{
pinMode(A0, INPUT);  
Serial.begin(9600);
}
void loop()
{
  int lightRead = analogRead(A0);
  Serial.println(lightRead);
  delay(5);
}
# analog sensor explaination
Briefly, this analog sensor is light read sensor, this sensor senses different readings by connecting this sensor to analog pin in arduino (A0) and connecting this sensor to the oscilloscope. I have observed that when we vary the readings or measurements of the sensor, the oscillscope gives any value at any time so this is the reason of calling this sensor as an analog sensor because it is reading any value at any time. 
