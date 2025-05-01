
# OLED Shooter Game (Arduino)

A simple arcade-style shooting game for Arduino with SSD1306 OLED display and push buttons.

## Hardware Required:
- Arduino UNO/Nano
- 128x64 I2C OLED Display (SSD1306)
- 3x Push Buttons (for Left, Right, Fire)
- Jumper Wires, Breadboard

## Pin Configuration:
- Left Button: D2
- Right Button: D3
- Fire Button: D4

## Libraries Used:
- [Adafruit GFX Library](https://github.com/adafruit/Adafruit-GFX-Library)
- [Adafruit SSD1306 Library](https://github.com/adafruit/Adafruit_SSD1306)

Install them via Arduino Library Manager.

## Gameplay Instructions:
- Use left/right buttons to move the player.
- Press fire to shoot.
- Each 10 points increases the level.
- Game over when enemy touches player.
- Press fire after game over to restart.

## Screenshot:
*(Add a photo or GIF of gameplay if available)*

## License:
MIT License
