# ArduinoLED
//Toying around with the RGB light on the Arduino

void showRGB(int color)
{

const int RED_PIN = 9;
const int GREEN_PIN = 10;
const int BLUE_PIN = 11;
}

 if (color <= 255)
{
redIntensity = 255 - color;
greenIntensity = color;
blueIntensity = 0;
}
else if color >= 512
{
redIntensity = 0;
greenIntensity = 255 - (color -256);
blueIntensity = 255 
