# Zombie Hand

![alt text](https://github.com/adahui/zombiehand/blob/master/build.PNG)

Materials needed:
- 1 Arduino Uno board
- 1 USB cable
- 1 servo motor
- 1 male-male red jumper cable
- 1 male-male black jumper cable
- 1 mini rubber hand
- 1 plastic knife blade
- 1 weight
- 1 roll of adhesive stripping

1. A miniature rubber hand was fixed onto the head of a plastic knife blade, which was taped to the servo motor at the normal (zero-degree position). The servo motor with the hand crawler was attached to a weight in order to keep the servo motor from toppling over while rotating. In this case, a safety light was used as a steadying support.

2. The hand crawler was connected to the Arduino Uno board with the following circuit plan.

- Hand crawler servo motor red power wire + male-male red jumper cable to Arduino Uno digital input power 5V
- Hand crawler servo motor white control wire + male-male yellow jumper cable to Arduino Uno digital output pin correspondent 7
- Hand crawler servo motor black ground wire + male-male black jumper cable to Arduino Uno digital input ground GND

3. The code was uploaded onto the Arduino Uno board.
