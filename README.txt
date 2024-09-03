Some pins have been changed

Before:| DIN | BCK | LRCK | SCK | SDA | SCL | RST |
       | 12  | 08  |  09  |  19 |  00 |  01 |  14 |

After:| DIN | BCK | LRCK | SCK | SDA | SCL | RST |
      | 26  | 27  |  28  |  NC |  NC |  NC |  NC |

POWER PINS: GND and VCC (5.5v)

//NOT CONNECTED

#define NEG_SWITCH_PWM_PIN 17

#define AUDIO_POS_SUPPLY_EN_PIN 22

#define PCM_I2C_ADDR 70