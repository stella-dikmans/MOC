# Museum Of Colonialization (MOC)

**with marielle, carolina & stella**

for a more viewer-friendly documentatino, visit our [notion page](https://www.notion.so/Marielle-Stella-Carolina-MDEF-22-23-34fdfc848ec44d93bae61fdf263d6c88)


**what we ask**

the background music to this project are some of our beloved reference (partly from social media) that put out leverage points through formulating questions...

What was more important “Single Ladies” by Beyonce or the Renaissance?

How is the city of Barcelona telling the stories of the past? Who is telling them and who has been silenced? What are statues of the dead trying to say?

What voices of the past are perpetuating illusions and why the end of those lies are hard to imagine?

**what we do** 

We are paying attention to the city’s street names, the wall paintings, statues and engravings as we believe they are constantly whispering half truths. History is being told by a very particular societal group that has imprisoned one half of the truth somewhere... This machiene exists because the present time was very poorly designed by a selective group. The machine will (intentionally) expose the dirty history of hidden public artifacts in order to embrace other futures (by other we mean the furthest point possible from patriarchy, capitalist and neo-colonist structures) so citizens can fully engage, at their own risk, with their cities history. 

**what we provide** 

We design a first prototype for a transparent gumball machine that contains easily digestible, fun(?) facts about the colonisers who have shaped the city. The idea is that one encounters it somewhere in the city, presses a button and opens the (paper) ball received. Inside, one finds a sticker with the image of a coloniser and a fun(?) fact about that person. Opening the paper ball reveals a letter asking the reader to follow the given coordinates and place the stickers at the location - which will be associated with the (legacy of the) person on the sticker. We aim to raise awareness and engage white citizens (whiteness here as a concept of power and privilege of the dominant group in society) who do not think about the people who were and are celebrated as homeland heroes, let alone know about their terrible deeds, and are often not interested enough to research the history themselves. that is why the machiene is supposed to operate in the multiverses of Barcelona and spit out the balls to those who actively make a promise to obtain knowledge. We call this gumball machine, the *museum of colonialization* (MOC).

# how we got there - in theory

the first phases are thinking processes about how we want people to engage with the colonial past of the city. We come up with ideas of a toolkit to cast immeediate environments and transform them into stamps, we think about pasting QR-codes onto statues that would lead to a digital environment of knowledge transmission. Soon we venture to the idea of having a gumball machine that in exchange for a promise spits out little versions of the statues that are to be found in the city with their coordinates and some unpopular funny (or rather cynic?) facts about their background. We early on in the process agree upon making knowledge easily digestiable, not speaking to an intellectual public that(probably anyways) is concerned with the theme of (de)colonial practices but instead speak to all those people walking the streets without paying attention to the (come on, actually pretty obvious) colonial legacies. Ok, so far so good, now it is just a matter of making a machiene that has a mechanism that spits out something (a ball) when pressing a buttom (to involve some arduino and coding here), little scultures that can be (dis)assembled (maybe press-fit with the lasercut), stickers on which there are coordinates and fun(?) facts about the represented persons (vinylcut), balls that can contain these sculptures (origami-shapes cut with laser or vinyl), and of course the research on the people we would like to display (our intellect of using the world wide web). We devide tasks. Even if one of our main overlaps is anti-economic-growth, the division-of-labor-thought serves well in the right moments (also we unfortunately put ourselves into a system that operates based on progress and output). Together, Marielle and Carolina would design the look of the gumball machine. Then, Marielle would take over the mechanic parts and with their arduino skills. With the help of Carolina whereever she would be helpful and has time to do so. Furthermore, Carolina would be busy with designing the contents about the colonizers - whereas the research we would do the three of us. Due to expected time-limitation we already here decide to pick each one person that is represented somehow in the city of Barcelona and each focus on some facts about that person. Stella would be concerned with the design of the ball for now and then help where needed. We have another idea att that moment. Maybe, a promise is not enough? What if we could create an application that opens the camera app automatically, and registered whether a photo of the stickered statue is hashtagges somewhere on social media? Well, wee see, that might be something for another iteration. For now, lets start crafting...

# how we got there - in practice

well, as always in these things, time flies by and suddenly we realize that our eyes were bigger than out stomachs - or better, our ideas were faster than our learning capacities. 

## the first prototypes
in designing the prototype, we fuse architectural components from different places (relevant to us), mainly from china town(s) and indigenous and traditional Angolan houses. The use of rounded corners and few straight lines is intentional to express the emotionally charged theme and the many inspiring unputs.

<img src="/imagery/design.jpeg" width="600" >

then, from cardboard and paper we of built the first prototypes of the insides of the **the gumball machine** which went quit well. It had do be somekind of turning wheel with for making the **motor spinning 180º** we took following steps:

    - Code
    - Servo.h library
    - Arduino setup
    - Changed to ESP32 

here you see a moving images of our [first trials](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/16466796-0670-4749-b0e5-d27b048bc41f/arduino1.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20230219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20230219T130231Z&X-Amz-Expires=86400&X-Amz-Signature=dd2166e426ab840216167c5a63f7f90af6ed1a5a367d03f8d9d344bf6cb7601e&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22arduino1.mp4%22&x-id=GetObject). Then we have some issues with deciding about the size of it all, as you can read about a bit further on, so we soon make a [bigger iteration](https://youtu.be/VP3YisYTgyI). And then soon we advance from cardboard to our[plexi-prototype](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/6f3e51df-b64f-4ac3-bc74-2265a9690209/arduino3.mp4?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20230219%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20230219T130303Z&X-Amz-Expires=86400&X-Amz-Signature=5594071d212c1295036f7952dda33d8a3e41e05c4af909ba15dbb604cf77d592&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22arduino3.mp4%22&x-id=GetObject)

and this is how the assembled board looks like after few set ups and with the cut plexi glass 

<img src="/imagery/arduino2.jpg" width="600" >

okay, now there this documentation will switch for a second to the design of the balls as there are defining the sequential problematics we cencounter with the mechanics of the machiene itself... for making of the **origami spheres** we took following steps:

    - getting to know origamisimulator.org (origami model visualization)
    - researching origami-simulator library for a fitting design
    - adapting the design according to our needs
    - translating the (rhino)file into a file readable by the lasercutter (lasercutter software)
    - laser-cutting the piece in paper (includes the trial of power and speed of laser)
    - folding the paper into balls
    - adapt size and form of the sphere in rhino
    - translating the rhino file into a file readable by the vinylprinter (silhuette studio software)
    - vinyl-printing the piece onto paper (includes the trial of blade-depth and force of vinyl-knife)
    - folding the paper into balls

for this design, we make use of an online [origami-simulator](https://origamisimulator.org/) that would show us how a folding-pattern for a sphere would look like. It is a prototyping tool that is supposed to speed up the process of complex origami shapes (definetely the sphere...). In our case, it worked out semi-professonial I would say.

the [origami-simulator](https://origamisimulator.org/) is designed by [an amanda](https://github.com/amandaghassaei/OrigamiSimulator) who very helping explains how things work and offer some example files on her [github page](https://github.com/amandaghassaei/OrigamiSimulator). Yet to understand all of this, it took some time and too figure that files can be created and adapted in rhino to work in the simulator, took some more. To explain it short here, she has some [example files](https://github.com/amandaghassaei/OrigamiSimulator/tree/main/assets) under which one of an amazing [sphere](https://github.com/amandaghassaei/OrigamiSimulator/blob/main/assets/Curved/Origami_Sphere_16Flaps.svg) and the [simulation](https://origamisimulator.org/) shows clearly how it folds and unfolds. We download this file, open it in rhino, explode the existing design and define groups and color codes anew, accoding to our needs. The online simulator reads SVGs in one way (File - Design Tips on the [simulator](https://origamisimulator.org/)) (Mountain folds have red stroke - rgb(255, 0, 0), hex #ff0000; Valley folds have blue stroke - rgb(0, 0, 255), hex #0000ff; Boundary edges have black stroke - rgb(0, 0, 0), hex #000000) which can vary from the rules used in the lasercutter- and the vinylprinter software. Here often you can define the actions and allocate them to colors of choice. But its important to keep in mind that the simulation SVGs doo not necessarily have the same color-codes as the rhino-files used for printing. Once created or adapted the rhino-file, we export it as an SVG and uplad it into the simulator. My first trials where kind of beautful yet definetely not as expected. 

<img src="/imagery/trial1pattern.png" width="600" >
<img src="/imagery/trial1.png" width="600" >

here you can see [the simulation](https://www.youtube.com/watch?v=6CcZ05MdBGI)

<img src="/imagery/trial2pattern.png" width="600" >
<img src="/imagery/trial2.png" width="600" >

okay, once we find that it works, we try to immitade [amandas](https://github.com/amandaghassaei/OrigamiSimulator) design by ourselves and play with some drawings in rhino, then we subsequentially upload into the simulator and print in the vinylcutter.

<img src="/imagery/trial3pattern.png" width="600" >
<img src="/imagery/trial3.png" width="600" >

here you can see [the simulation of the almost final piece - something is still wrong](https://www.youtube.com/watch?v=sKiC5CueAeU).

so in the end we sticked to [amandas](https://github.com/amandaghassaei/OrigamiSimulator) file and just adapted the size to a A3 length in order to make it handy when printing. And look there, the fold paper looks prettty much like the simulation. In the end, what does it matter if we created the file ourselves or downloaded other peoples work? sharing is caring and I am sure amanda out them out there for us to make use of them. 

<img src="/imagery/trial4pattern.png" width="600" >
<img src="/imagery/trial4.png" width="600" >

<img src="/imagery/gumballs_armadillo.jpg" width="600" >

<img src="/imagery/armadillosfinal.png" width="600" >

a few more things that came up while cutting and printing... we use paper (because we want to print text on them and have the hapticity of a entrance ticket or letter or something foldable that is easy to pocket away), meaning tha engraving the pattern in order to make fold easier have to be very precise not to cut through fully. 

my experience with the lasercut. I tried a variety of power and speeds
<img src="/imagery/lasertrials.JPG" width="600" >

and in the end came up with this settings (yet they vary for each lasercutter. I tried with another lasercutter and it was way to heavy there) 

<img src="/imagery/lasercutter.JPG" width="600" >

but for the actual armadillos we did not make use of the lasercutter (mostly due to bad organization and availabilty of the lasercutter) but instead used the vinylcutter. This takes way longer and about the precision can be fought. But it had two great advantages... we could take it with us and for that work on it with immediate adaptations and because it has a blade instead of a laser, there are no traces of burning material to be seen in the end piece. 

for the vinyl print the final settings were the lowest possible for the folds and the standard cutting ones for the outline.

<img src="/imagery/vinylprint.png" width="600" >

okay, the making of the balls was thought to be the most easy and time-least intense task yet it turns out to keep us busy for quite some hours, days and evenings. In the end, we made it to these little creatures that thanks to Myrto got the name Armadillos (because they look like them...). Here you can see them in [action](https://www.youtube.com/shorts/NzCeEY9-zz4)


okay, back to the bigger machine in which we now can cooperate the size of the **armadillos**. We adapt the **dispenser disk according to the ball size** and encounter quit some struggles:
        
        struggling to get a cross that would not interfere with the motor movement. we have two options: 
        
        1 - origami cross, with came up with a cross that almost did not have to cut anything but was hard to manipulate using cardboard; 
        
        2 - crisscross two rectangles by fitting them together - puzzle like. 
        
        We went for the second option as it ended up working the best for cardboard prototyping
        
    - ball with 10cm - dispenser has axis with 20cm
    - the frame is a circumference with 23 cm of diameter. It was drawn with a improvised compass (tape, cutter, tape), so it is not the most neat but enough to fulfill its purpose
    


<img src="/imagery/compass_dispenser.jpg" width="600" >

<img src="/imagery/disk_making.jpg" width="600" >



okay, once we have the internal working, we could move on to the outside design. So, we are envisioning the **outer body of the machine (according to dispenser disk and ball size)** based on cultural and ancestral knowledges as we alerady explain above a bit.

<img src="/imagery/museum_sketches.jpg" width="600" >


we then rapidly prototype witthout any measurements, just having the first prototyped ball as a reference angle. In order to get the rounded shapes and edges, we need to have a bending material that would give the illusion of softness. With cardboard, this works very well, so we move on to other materials and try out patterns that help obtain a flexible structure in woods with **laser kerf patterns**. We really like the results as we figure there is a very Afrofuturistic aura to it :)

For this, we design in Adobe Illustrator and translate into a rhino 5 file to make it readable for the laser cutter in the FabLab. 
        
<img src="/imagery/patterns_wood.jpg" width="600" >

watch here some of the results of [our experiments](https://www.youtube.com/watch?v=FstxQJzx4rc)

the first wood we work on is a good material for laser cutting. It burns very fast - making it brittle. Still, we could tell which of the designs were the most flexible. However, in the end we decide to stick to the easypeasyness of the many potentialities of cardboard. 



**We are now using cardboard with a stripped layer - very flexible, light and has a wonderful texture (almost ancestral like)**

<img src="/imagery/museum_day.before.presentation.jpg" width="600" >

- **Preparing for the final prototype**
    - Slots testing for fitting the front and back panels to the base of the “museum machine”
    - 2D drawing of the front of the museum
    - drawing the stickers of the “colonizers & friends”

<img src="/imagery/slots_test.jpg" width="600" >

<img src="/imagery/frontview_museum.jpg" width="600" >

<img src="/imagery/stikers1.jpg" width="600" >

and heeeere in it's preliminary final state
<img src="/imagery/final.jpg" width="600" >


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

## Chistopher Columbus:
 [Christopher Columbus](https://www.google.com/maps/place/Columbus+Monument/@41.3765654,2.1730909,15.52z/data=!4m6!3m5!1s0x12a4a256d7bd004b:0x2adc0acddfeb6cb7!8m2!3d41.3758087!4d2.1777606!16s%2Fm%2F04crww4) 

 - coordinates of the sculpture in the city of Barclone (Lat and Long) 41.376363370357524, 2.1776672290079175

[Christopher Columbus (1)](Chistopher%20Columbus%2083b9fcd5d72e40aeb52aa30bb2df90a8/Christopher%20Columbus%20(1)%2053686794a0824f43a483923dfcefeea6.md)

<img src="/imagery/Screenshot_2023-02-15_111906.png" width="600" >

[Columbus was a mass killer and the father of the slave trade](https://www.notion.so/Marielle-Stella-Carolina-MDEF-22-23-34fdfc848ec44d93bae61fdf263d6c88)

- Considered the founding father of the slave trade
- Responsible for 3 Millions Deaths

**[Was Christopher Columbus a Hero or Villain?](https://www.biography.com/history-culture/christopher-columbus-day-facts)****

- Many people already believed the world was round


## Joan Prim I Prats

 - coordinates of the sculpture in the city of Barclone (Lat and Long) 41.39979966550844, 2.1891571903125313

An appointed governor of Puerto Rico at a point in time within these pivotal shifts was Joan Prim y Prats. As acting captain-general (governor) of the island, he created the most infamous Decree against the African race in 1848, only one year after he was delegated to office. Bando Contra La Raza Negra [Decree Against the African Race] was a repressive and punitive decree that made no distinction between free Africans, People of Color and slaves.


## Guell & the others

 - coordinates of the sculpture in the city of Barclone (Lat and Long) 41.423676898281464, 2.1510620122173028

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

<img src="/imagery/finalstickersimage.png" width="600" >

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

[MOC in action](https://www.youtube.com/watch?v=h7pCk-1pPlY)

**attempts with origami:**

our armadillo

based of orgimai spheres

[origami-simulator](https://origamisimulator.org/)

our origami hero amanda

[and their gitbug shares](https://github.com/amandaghassaei/OrigamiSimulator)




## the preliminary final
