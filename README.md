# Museum Of Colonialization (MOC)


'with marielle, carolina & stella'


# our process

**Silly description:** We are paying attention to the city’s street names, the wall paintings, statues and engravings as we believe they are constantly whispering half truths. History is being told by a very particular societal group that has imprisoned one half of the truth somewhere... This machine exists because the present time was very poorly designed by a selective group. The machine will (intentionally) expose the dirty history of hidden public artifacts in order to embrace other futures (by other we mean the furthest point possible from patriarchy, capitalist and neo-colonist structures) so citizens can fully engage, at their own risk, with their cities history.

**Questions: “**What was more important “Single Ladies” by Beyonce or the Renaissance?” ****How is the city of Barcelona telling the stories of the past? Who is telling them and who has been silenced? What are statues of the dead trying to say? What voices of the past are perpetuating illusions and why the end of those lies are hard to imagine? 

## Cardboard and paper prototype

- **Ball making**
    - laser cut - foldable model
    - origami model visualization
    - adapt the size of the ball
    - design a new version adapted to our machine
    - come back to the initial design

![gumballs_armadillo.jpg](imagery/gumballs_armadillo.jpg)

**The last one in the picture was the best! We are calling these Armadillos, because they look like one (thank you Myrto for the tip!)**

- **Motor spinning 180º**
    - Code
    - Servo.h library
    - Arduino setup
    - Changed to ESP32 

[first trial](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/16466796-0670-4749-b0e5-d27b048bc41f/arduino1.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20230217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20230217T115311Z&X-Amz-Expires=86400&X-Amz-Signature=f01d4c50d05be26c97f73d54fc8e929b2bec7cedc6c3a69cae4bc201cb3cebe8&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22arduino1.mp4%22&x-id=GetObject)

[getting there](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/6f3e51df-b64f-4ac3-bc74-2265a9690209/arduino3.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20230217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20230217T120425Z&X-Amz-Expires=86400&X-Amz-Signature=81d2612c4e63dc13ea00c61125af380e77237c1fd2cc3fde751f286a6007b75d&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22arduino3.mp4%22&x-id=GetObject)

![the board](imagery/arduino2.jpg)

- **Dispenser disk according to the ball size**
    - struggles
        
        struggling to get a cross that would not interfere with the motor movement. 2 options: 
        
        1 - origami cross, with came up with a cross that almost did not have to cut anything but was hard to manipulate using cardboard; 
        
        2 - crisscross two rectangles by fitting them together - puzzle like. 
        
        ***We went for the 2nd option as it ended up working the best for cardboard prototyping***
        
    - ball with 10cm - dispenser has axis with 20cm
    - the frame is a circumference with 23 cm of diameter. It was drawn with a improvised compass (tape, cutter, tape), so it is not the most neat but enough to fulfill its purpose
    

![compass_dispenser.jpg](imagery/compass_dispenser.jpg)

![disk_making.jpg](imagery/disk_making.jpg)

[succes](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/82e5323b-2eed-4eb0-b4e5-41193e756244/dispenser_prototype.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20230217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20230217T120925Z&X-Amz-Expires=86400&X-Amz-Signature=7868c0731bf06cbb774e504740ac7d9c45651776f1d6d8c4a853bca25270f8f5&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22dispenser_prototype.mp4%22&x-id=GetObject)

- **Outer body of the machine (according to dispenser disk and ball size)**
    - envisioning it based on cultural and ancestral knowledge
    
    ![museum_sketches.jpg](imagery/museum_sketches.jpg)
    
    - rapid prototyping without many measurements. Doing it based on the disk and ball size.
    - bended base of the machine: after the cardboard prototyping we moved on to patterns that help obtain a flexible structure
        - **laser kerf patterns** on Adobe Illustrator and passed to rhino 5 for laser cutting in FabLab
        - it also has a very Afrofuturistic aura to it :)
        

- the first wood we worked on was a good material for laser cutting. It burned very fast - making it brittle. Still, we could tell which of the designs were the most flexible.

![patterns_wood.jpg](imagery/patterns_wood.jpg)

**We are now using cardboard with a stripped layer - very flexible, light and has a wonderful texture (almost ancestral like)**

![museum_day.before.presentation.jpg](imagery/museum_day.before.presentation.jpg)

- **Preparing for the final prototype**
    - Slots testing for fitting the front and back panels to the base of the “museum machine”
    - 2D drawing of the front of the museum
    - drawing the stickers of the “colonizers & friends”

![slots_test.jpg](imagery/slots_test.jpg)

![frontview_museum.jpg](imagery/frontview_museum.jpg)

![stikers1.jpg](imagery/stikers1.jpg)



# making it work electronically: code

[ButtonSwitch.ino](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/87337473-5b58-4257-bee7-4c66571b34b5/ButtonSwitch.ino?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20230217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20230217T122434Z&X-Amz-Expires=86400&X-Amz-Signature=35114100168a7e96b715659e506278d87c663e4fb132c3d4027a9798452e2593&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22ButtonSwitch.ino%22&x-id=GetObject)

**FINAL MOTOR CODE WITH SERVO.H (LIBRARY) FOR ESP32 - ARDUINO IDE**

```jsx
/*
 * Created by ArduinoGetStarted.com
 *
 * This example code is in the public domain
 *
 * Tutorial page: https://arduinogetstarted.com/tutorials/arduino-button-servo-motor
 */

#include <ESP32Servo.h>

// constants won't change
const int BUTTON_PIN = 36; // Arduino pin connected to button's pin
const int SERVO_PIN  = 4; // Arduino pin connected to servo motor's pin

Servo servo; // create servo object to control a servo

// variables will change:
int angle = 0;          // the current angle of servo motor
int lastButtonState;    // the previous state of button
int currentButtonState; // the current state of button

void setup() {
  Serial.begin(9600);                // initialize serial
  pinMode(BUTTON_PIN, INPUT_PULLUP); // set arduino pin to input pull-up mode
  servo.attach(SERVO_PIN);           // attaches the servo on pin 9 to the servo object

  servo.write(angle);
  currentButtonState = digitalRead(BUTTON_PIN);
}

void loop() {
  lastButtonState    = currentButtonState;      // save the last state
  currentButtonState = digitalRead(BUTTON_PIN); // read new state
   Serial.println(currentButtonState);

  if(lastButtonState == HIGH && currentButtonState == LOW) {
    Serial.println("The button is pressed");

    // change angle of servo motor
    if(angle == 0)
      angle = 180;
    else
    if(angle == 180)
      angle = 0;

    // control servo motor arccoding to the angle
    servo.write(angle);
  }
}
```