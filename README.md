# Arduino-Piano-Project
Arduino piano project using push buttons and buzzer
int buzzer = 8;
void setup() {
}
void loop() {
  tone(buzzer, 262); // Sa
  delay(1000);

  tone(buzzer, 294); // Re
  delay(1000);

  tone(buzzer, 330); // Ga
  delay(1000);

  tone(buzzer, 349); // Ma
  delay(1000);
}
