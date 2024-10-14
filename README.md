پروژه چاپ متن در serial monitor
void setup() {
  // put your setup code here, to run once:
Serial.begin(9600);
}

void loop() {
  // put your main code here, to run repeatedly:
Serual.println("Hello word!");
delay(1000);
}
در این کد جمله "helle word" را هر یک ثانیه یک بار در serial monitor چاپ میکند
