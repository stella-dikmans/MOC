# Museum Of Colonialization (MOC)

**with marielle, carolina & stella**

for a more user-friendly documentatino, visit our [notion page](https://www.notion.so/Marielle-Stella-Carolina-MDEF-22-23-34fdfc848ec44d93bae61fdf263d6c88)
 
**Silly description:** We are paying attention to the city’s street names, the wall paintings, statues and engravings as we believe they are constantly whispering half truths. History is being told by a very particular societal group that has imprisoned one half of the truth somewhere... This machine exists because the present time was very poorly designed by a selective group. The machine will (intentionally) expose the dirty history of hidden public artifacts in order to embrace other futures (by other we mean the furthest point possible from patriarchy, capitalist and neo-colonist structures) so citizens can fully engage, at their own risk, with their cities history.

Questions: 

**What was more important “Single Ladies” by Beyonce or the Renaissance?”**

**How is the city of Barcelona telling the stories of the past? Who is telling them and who has been silenced? What are statues of the dead trying to say?**

**What voices of the past are perpetuating illusions and why the end of those lies are hard to imagine?**

# process
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

moving images of our [first trials](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/16466796-0670-4749-b0e5-d27b048bc41f/arduino1.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20230217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20230217T115311Z&X-Amz-Expires=86400&X-Amz-Signature=f01d4c50d05be26c97f73d54fc8e929b2bec7cedc6c3a69cae4bc201cb3cebe8&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22arduino1.mp4%22&x-id=GetObject) and how we are slowely[getting there](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/6f3e51df-b64f-4ac3-bc74-2265a9690209/arduino3.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20230217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20230217T120425Z&X-Amz-Expires=86400&X-Amz-Signature=81d2612c4e63dc13ea00c61125af380e77237c1fd2cc3fde751f286a6007b75d&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22arduino3.mp4%22&x-id=GetObject)

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

and a moving image of how we happily made it happen: [successsssssss](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/82e5323b-2eed-4eb0-b4e5-41193e756244/dispenser_prototype.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20230217%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20230217T120925Z&X-Amz-Expires=86400&X-Amz-Signature=7868c0731bf06cbb774e504740ac7d9c45651776f1d6d8c4a853bca25270f8f5&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22dispenser_prototype.mp4%22&x-id=GetObject)

- **Outer body of the machine (according to dispenser disk and ball size)**
    - envisioning it based on cultural and ancestral knowledges
    
    ![museum_sketches.jpg](imagery/museum_sketches.jpg)
    
    - rapid prototyping without many measurements. Doing it based on the disk and ball size.
    - bended base of the machine: after the cardboard prototyping we moved on to patterns that help obtain a flexible structure
        - **laser kerf patterns** on Adobe Illustrator and passed to rhino 5 for laser cutting in FabLab
        - it also has a very Afrofuturistic aura to it :)
        
![patterns_wood.jpg](imagery/patterns_wood.jpg)

- the first wood we worked on was a good material for laser cutting. It burned very fast - making it brittle. Still, we could tell which of the designs were the most flexible. 
However, in the end we decided to stick to the easypeasyness of the many potentialities of cardboard. 

**We are now using cardboard with a stripped layer - very flexible, light and has a wonderful texture (almost ancestral like)**

![museum_day.before.presentation.jpg](imagery/museum_day.before.presentation.jpg)

- **Preparing for the final prototype**
    - Slots testing for fitting the front and back panels to the base of the “museum machine”
    - 2D drawing of the front of the museum
    - drawing the stickers of the “colonizers & friends”

![slots_test.jpg](imagery/slots_test.jpg)

![frontview_museum.jpg](imagery/frontview_museum.jpg)

![stikers1.jpg](imagery/stikers1.jpg)

and heeeere in it's preliminary final state
![final.jpg](imagery/final.jpg)


## making it work electronically: code

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

## about the content of the armadillos

we updated out initial idea of making small little scultures with a QR-code or a sticker that the receivers would need to stick to the actual scultpure. In the end, who wants to have a colonizer as a little sculture? also, we don't even want people to know their faces let alone seeing them all the time. So we just stick to the stickers - and of course the promise to actually put that sticker into the public sphere...

## colonizer Stickers

for now we choose three figures to unconver theirs deeds and raise awareness about. Maybe, making a little bit fun of them. This is mainly due to time and energy-resources available to us during this short challenge-week. there is a infinte amount of people, scultures, habits, unrecognized heritages that we could reveil here and let our armadillos spread the words.

we decided for now on three rather famous ones that are prominent in barcelonas skyline...

Chistopher Columbus:
 [Christopher Columbus](https://www.google.com/maps/place/Columbus+Monument/@41.3765654,2.1730909,15.52z/data=!4m6!3m5!1s0x12a4a256d7bd004b:0x2adc0acddfeb6cb7!8m2!3d41.3758087!4d2.1777606!16s%2Fm%2F04crww4) - coordinates in Lat and Long: 41.376363370357524, 2.1776672290079175

[Christopher Columbus (1)](Chistopher%20Columbus%2083b9fcd5d72e40aeb52aa30bb2df90a8/Christopher%20Columbus%20(1)%2053686794a0824f43a483923dfcefeea6.md)

![Screenshot 2023-02-15 111906.png](imagery/Screenshot_2023-02-15_111906.png)

[Columbus was a mass killer and the father of the slave trade](https://www.notion.so/Marielle-Stella-Carolina-MDEF-22-23-34fdfc848ec44d93bae61fdf263d6c88)

- Considered the founding father of the slave trade
- Responsible for 3 Millions Deaths

****[Was Christopher Columbus a Hero or Villain?](https://www.biography.com/history-culture/christopher-columbus-day-facts)****

- Many people already believed the world was round


Joan Prim I Prats

An appointed governor of Puerto Rico at a point in time within these pivotal shifts was Joan Prim y Prats. As acting captain-general (governor) of the island, he created the most infamous Decree against the African race in 1848, only one year after he was delegated to office. Bando Contra La Raza Negra [Decree Against the African Race] was a repressive and punitive decree that made no distinction between free Africans, People of Color and slaves.
Guell & the others
***Eusebio’s Guell father - Joan Guell - made a fortune from the slave trader. His son inherented those richness.***

[https://www.foreverbarcelona.com/count-eusebio-guell/](https://www.foreverbarcelona.com/count-eusebio-guell/)

It is worth noting that Spain did not approve the law establishing the abolition of slavery in Cuba until 1880 and that there were anti-abolitionist leagues and demonstrations in many cities around Spain during the same period.

People like signed a manifesto against the abolition of slavery in Cuba: two future bishops, Morgades and Casañas; intellectuals like Rubió i Ors and Duran i Bas; physicians like José de Letamendi; and industrialists and bankers like Güell, Arnús and Ferrer i Vidal. 

[https://www.thenewbarcelonapost.com/en/barcelona-1300-km-of-streets-and-some-controversies/](https://www.thenewbarcelonapost.com/en/barcelona-1300-km-of-streets-and-some-controversies/)

Colonia Guell was created in “reaction to unfavorable popular opinion of Güell among labor groups, who viewed him as “one of the ‘big fish’ who was keeping the workers enslaved” and representing “scheming clerical-colonial interests.””

[https://washingtoncollegereview.files.wordpress.com/2019/09/wysong_a-sea-of-equilibrium-antoni-gaudicc81e28099s-political-undercurrent.pdf](https://washingtoncollegereview.files.wordpress.com/2019/09/wysong_a-sea-of-equilibrium-antoni-gaudicc81e28099s-political-undercurrent.pdf)

**furthermore**

[Barcelona discovers its slavery inheritance - EUROM](https://europeanmemories.net/press/barcelona-discovers-its-slavery-inheritance/)

["A black woman with no defects for sale": The last slave drivers were Spanish](https://aldianews.com/en/culture/heritage-and-history/last-slaveowners)

[Barcelona’s slave trade history revealed on new walking tour](https://www.theguardian.com/travel/2016/apr/13/barcelona-slave-trade-history-new-walking-tour-catalonia-spain-ramblas)

## **Final stickers >**

![finalstickersimage.png](imagery/finalstickersimage.png)



# References & Resources

**1st Attempt with Arduino:**

Servo Motor 

1. [https://www.youtube.com/watch?v=SNE8axnq9gI](https://www.youtube.com/watch?v=SNE8axnq9gI)
2. [https://www.electronics-lab.com/project/using-sg90-servo-motor-arduino/](https://www.electronics-lab.com/project/using-sg90-servo-motor-arduino/) - USED ✅

Button Press & Servo

1. [https://arduinogetstarted.com/tutorials/arduino-button-servo-motor](https://arduinogetstarted.com/tutorials/arduino-button-servo-motor) - USED ✅

**2nd Attempt with ESP32:**

ESP32 Servo Motor Library

- *Coding, commands and functions very similar to the Arduino version*

[https://github.com/RoboticsBrno/ServoESP32](https://github.com/RoboticsBrno/ServoESP32) - USED ✅

[https://www.hackster.io/neosteam-labs/project-11-esp32-feather-push-button-mk02-e87dd3](https://www.hackster.io/neosteam-labs/project-11-esp32-feather-push-button-mk02-e87dd3)

- *Understanding better the command with Daphne -* [https://randomnerdtutorials.com/esp32-servo-motor-web-server-arduino-ide/](https://randomnerdtutorials.com/esp32-servo-motor-web-server-arduino-ide/)

**Mechanisms:**

1. [https://www.youtube.com/watch?v=aomavIH9Y64](https://www.youtube.com/watch?v=aomavIH9Y64) - EXPERIMENTED WITH in order to understand the mechanism behind the gumball machines
2. [https://www.youtube.com/watch?v=8kRTpmswgFk](https://www.youtube.com/watch?v=8kRTpmswgFk)
3. [https://makezine.com/projects/secret-knock-gumball-machine//?utm_source=sumome&utm_medium=pinterest&utm_campaign=sumome_share](https://makezine.com/projects/secret-knock-gumball-machine//?utm_source=sumome&utm_medium=pinterest&utm_campaign=sumome_share)
4. [https://www.youtube.com/watch?v=Z5GADxTa1sA](https://www.youtube.com/watch?v=Z5GADxTa1sA)

**HOW DO GUMBALL MACHINES WORK? GREAT ANIMATION EXPLAINING THE MECHANISMS**

[https://www.youtube.com/watch?v=Q3ZeUNDg4fQ](https://www.youtube.com/watch?v=Q3ZeUNDg4fQ)

**attempts with origami:**

our armadillo

based of orgimai spheres

[origami-simulator](https://origamisimulator.org/)

our origami hero amanda

[and their gitbug shares](https://github.com/amandaghassaei/OrigamiSimulator)


