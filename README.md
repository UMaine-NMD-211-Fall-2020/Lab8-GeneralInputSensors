# Lab8: General Input Sensors
In this lab, you will learn to use your choice of  2 input sensors, so that you can trigger events in at least 3 ways. These inputs will be used with your lanterns.  This is not the end of the lanterns!

## Steps
0. Explanation of your lanterns to class
1. Exploration of Sensor 1
2. [EXTRA] Exploration of Sensor 2
3. Use all 2 input sensors
4. Make your code from last week, the RGB LED / Push button joint code more concise or efficient. Use functions or classes. 
## To Submit
Upload the following to your google drive folder or link to your file via github. Only the code needed to take in input is necessary - feel free to use an LED to show that input was received, or take a screenshot of print statements that show that the values are getting through. In the case of a print statement, it needs to state what the values we see are as well as state the 

### 1: Explore Sensor 1
1. State your first input sensor of choice. Why did you choose it? Did you make use of all of it's capabilities. If not, which capabilities did you use, and what drove that choice? Do you understand where to find more data on how to use these sensors?
2. Describe what how you got input from this sensor.
- Electrical diagram with explanation
- Picture of your setup
- Video of what is happening
- Properly commented code, zipped, with naming scheme: Lab8_Sensor1_FirstName_LastName 
3. Document any difficulties you ran into. How did you fix them? Links/screenshots or brief written descriptions as appropriate. If there were none, say so. 
4. What would you need to do to use this input in your lantern design?
### 2: Explore Sensor 2 [EXTRA CREDIT]
1. State your second input sensor of choice. Why did you choose it? Did you make use of all of it's capabilities. If not, which capabilities did you use, and what drove that choice? Do you understand where to find more data on how to use these sensors?
2. Describe what how you got input from this sensor.
- Electrical diagram with explanation
- Picture of your setup
- Video of what is happening
- Properly commented code, zipped, with naming scheme: Lab8_Sensor2_FirstName_LastName 
3. Document any difficulties you ran into. How did you fix them? Links/screenshots or brief written descriptions as appropriate.
4. What would you need to do to use this input in your lantern design?
### 3: Combine 2 sensors
Look at your documentation from last week's push buttons as well as this week's sensor. 
1. Draw a electrical diagram that shows how to connect all 2 sensors into one working circuit.  Explain what is happening. 
2. Set up the circuit. Take pictures. 
3. Write the code that combines all of these. Use LEDS/ RGB LEDS to differentiate between getting different types of inputs. Take video.
4. Show this working in your lantern. Take video. 
5. Document any difficulties / issues.  If there were none, say so. 
### 4: Code efficiency
1. Submit a zip file with your joint push button / RGB LED code from last week, made more efficient. Don't hardcode, use functions, use classes as appropriate. Make sure to run it on your arduino to see that it still compiles properly before turning this in. 

## Useful Resources
### Input Sensors to choose from
#### RC522 RFID Module
This is a secure way to trigger events - it's basically an unlocking mechanism.

- [Written Details](https://components101.com/wireless/rc522-rfid-module)
- [Useful Video](https://youtu.be/So83sH6-jwM) Shows you how to use the RFID tag. The display portion is an output bit which we can skip for now. 
#### GY-521 Module (Accelerometer / Gyroscope / Temperature Sensor / Digital Motion Processor)
Measures if something has been moved or turned, the speed at which it goes, and the temperature

- [Written Details](https://electrosome.com/interfacing-mpu-6050-gy-521-arduino-uno/)
- [Useful Video](https://www.youtube.com/watch?v=wTfSfhjhAU0)
#### HC-SR501 PIR Motion Sensor
Detect motion!
- [Written Details](https://lastminuteengineers.com/pir-sensor-arduino-tutorial/)
- [Useful Video](https://youtu.be/g6K6K7rkg-s)

#### HC-SR501 PIR Motion Sensor
Detect motion!
- [Written Details](https://lastminuteengineers.com/pir-sensor-arduino-tutorial/)
- [Useful Video](https://youtu.be/g6K6K7rkg-s)

#### Sound Sensor
Detect sounds
- [Written Details](https://www.instructables.com/Arduino-Sound-Sensor-with-LED/)
- [Useful Video](https://youtu.be/RwHGioglbk8)

#### Water Level Detection Sensor 
Keep track of water levels
- [Written Details](https://theiotprojects.com/water-level-sensor-arduino-tutorial/)
- [Useful Video](https://youtu.be/n7WRi5U5lQk)


#### Ultrasonic Sensor Module
Determine how far away something is
- [Written Details](https://www.tutorialspoint.com/arduino/arduino_ultrasonic_sensor.htm)
- [Useful Video](https://youtu.be/WslzsHDYuF0)

#### DS1307 RTC(Real Time Clock)
Input Time from the real world. 
- [Written Details](https://www.electronics-lab.com/project/ds1307-rtc-module/)
- [Useful Video](https://youtu.be/drU3dQa-8CE)

#### Rotary Encoder 
Have knob, change angle turned into digital data. Read [Rotary encoder vs potentiometer](https://www.arrow.com/en/research-and-events/articles/encoder-vs-potentiometer-how-to-choose#:~:text=The%20most%20obvious%20difference%20between%20rotary%20potentiometers%20and,clockwise%20or%20counter-clockwise%20before%20they%20need%20to%20stop.)
- [Written Details](https://electropeak.com/learn/rotary-encoder-how-it-works-how-to-use-with-arduino/)
- [Useful Video](https://youtu.be/zYE5JhUMjys)

#### DHT11 Temperature & Humidity Sensory
Take in temperature and humidity
- [Written Details](https://create.arduino.cc/projecthub/techno_z/dht11-temperature-humidity-sensor-98b03b)
- [Useful Video](https://youtu.be/OogldLc9uYc) 
#### IR Receiver
Infra Red data - to be used with remote control
- [Written Details](https://tutorial45.com/arduino-ir-receiver/)
- [Useful Video](https://youtu.be/3jeSfsnQOWk) 
#### Joystick
Joystick, just in case you want to make something like a game
- [Written Details](https://www.best-microcontroller-projects.com/arduino-joystick.html)
- [Useful Video](https://youtu.be/MlDi0vO9Evg) 
#### Potentiometer
Have knob, change angle turned into analog data. Read [Rotary encoder vs potentiometer](https://www.arrow.com/en/research-and-events/articles/encoder-vs-potentiometer-how-to-choose#:~:text=The%20most%20obvious%20difference%20between%20rotary%20potentiometers%20and,clockwise%20or%20counter-clockwise%20before%20they%20need%20to%20stop.)
- [Written Details](https://www.arduino.cc/en/tutorial/potentiometer)
- [Useful Video](https://youtu.be/RBYVUTIU4FE) 
#### Membrane Switch
Keypad
- [Written Details](https://randomnerdtutorials.com/arduino-membrane-keypad-tutorial/)
- [Useful Video](https://youtu.be/yE2mPGrqqg4) 


## How to Submit
Submit via Google Drive or by making a pull request and linking to your folder here.
- [FirstName LastName](www.example.com)
