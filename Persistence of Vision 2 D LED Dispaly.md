# Peersistence of Vision 2D LED Dispaly
## Error Analysis 
Error can occur due to loose connection in wiring so first we have to check the wiring 
We have to check if the LED in the Arduino is glowing .If it is not the Arduino is shorted somewhere so we need to change the arduino.
### LEDs:
We have to download the starter code for our Neo-pixel LEDs and give high to all the LEDs and check if they are working 
### Sensor:
Our entire logic is based on Hall sensor output value so we have to print the output of the hall sensor in serial monitor and bring a magnet nearby to check if it gives low when magnet is very closer to it 
If it is not we have to change the Hall sensor
### Motor :
To test the motor have available a variable voltage DC power supply (aka bench power supply)…one that can output relatively large amounts of power. Use a DC bench power supply to test your motor…to see whether it works. Always start off with very small voltage…then slowly and gradually increase the voltage until something spins. Also can be good to have a current meter in series with the motor to keep an eye on the current going into the motor.
To drive the motor, the Arduino’s low powered signal must be fed into a power module (like a relay device or power amplifier device) that can supply enough power to the motor. 
### Battery:
To check if the battery is working fine we have to check the output of the battery with a Voltmeter If the battery is in good condition, the voltage should show only slight variation from the specified voltage , If the difference is more we have to charge the battery 
