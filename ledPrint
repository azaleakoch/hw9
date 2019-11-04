int ledPin = 13;
int buttonPin = 8;
//if button press led go on and serial go aaaaaaaa

void setup() {
 pinMode(ledPin, OUTPUT);
 pinMode(buttonPin, INPUT_PULLUP);
 Serial.begin(9600);
}

void loop() {
 if (digitalRead(buttonPin) == LOW) {
 digitalWrite(ledPin, HIGH);
 Serial.println("aaaaaaa");
 
 }
 
 else {
 digitalWrite(ledPin, LOW);
 }
 
}
