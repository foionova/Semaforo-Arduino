  int ledG = 12;
  int ledY = 10;
  int ledR = 8;
void setup() {
  pinMode(ledG, OUTPUT);
  pinMode(ledY, OUTPUT);
  pinMode(ledR, OUTPUT);
}

void loop() {
  digitalWrite(ledG, HIGH);
  delay(1000);
  digitalWrite(ledG, LOW);
  digitalWrite(ledY, HIGH);
  delay(1000);
  digitalWrite(ledY, LOW);
  digitalWrite(ledR, HIGH);
  delay(1000);
  digitalWrite(ledR, LOW);
  digitalWrite(ledG, HIGH);
}
