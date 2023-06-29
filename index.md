# LED Scrolling Message Board
<!-- 
Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!
-->

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Uma A. | San Francisco University High School | Electrical Engineering | Incoming Sophmore

![Headstone Image](Uma-Headshot.png){:height="50%" width="50%"}
  
# Final Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## What you've accomplished since your previous milestone
Since my last milestone, I have attached my LED matrix onto a wood board, put brackets on all sides, and created a hole to hide the wires in. I also rewired the LEDs together because the other ones were too long and fell off. 

## What your biggest challenges and triumphs were at BSE

## A summary of key topics you learned about

## What you hope to learn in the future after everything you've learned at BSE


**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**



# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/qFt8fYEQzMg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Summary
After my first milestone, I changed my LEDs into a matrix and coded the LEDs to scroll words and form the message board.

### Components
- WS2812B LED; An LED is a  light-emitting diode is a semiconductor device that emits light when current flows through it. Electrons in the semiconductor recombine with electron holes, releasing energy in the form of photons. The color of the light is determined by the energy required for electrons to cross the band gap of the semiconductor
- BreadBoard; A breadboard, solderless breadboard, or protoboard is a construction base used to build semi-permanent prototypes of electronic circuits. Unlike a perf board or stripboard, breadboards are reusable and do not require soldering or destruction of tracks.
- Arduino Nano; Arduino is an open-source hardware and software company, project, and user community that designs and manufactures single-board microcontrollers and microcontroller kits for building digital devices.
I attached the end of the first LED to the power, ground, and digital pins. I attached the power wires to the power rail on the breadboard, and the ground wires to the ground rail. Then attached a jumper wire from the power and ground rail to a 5-volt power source. I attached the Arduino Nano to the breadboard and connected jumper wires from the 5-volt and ground pins to their perspective rails. I attached the control wires from the LEDs to the digital pins and installed a code to the Arduino Nano.

## Progress
- I connected the LED strips in a matrix form because the underlying principle here is that each LED can be addressed by specifying its location in terms of rows and columns. For example, the top-left LED is addressed as (A,1) i.e., row A, column 1. This method of addressing also indicates the flow of electrical current. In order to turn LED (A,1) on, current is caused to flow from A to 1. If switches are attached to each port A to D and 1 to 4, then, to turn the top-left LED on, switches A and 1 are made to conduct. The other LEDs will not have any current flowing because either their row or column switch is non-conducting.
- I have gotten the LEDs to display words with a new code I am using


## Challenges Faced 
- I shorted out my Arduino Nano because I had put my power jumper wire into the ground pin.
- In my code, I accidentally put in that the number of LEDs on each strip was 64, but after I tried the code I realized that it was wrong because the words were not able to be read. I recounted the number and it was 67.
  
## Next Steps 
- I need to move my wiring from the breadboard to a perf board
- put heat wrap around the connecting jumper wires
- find a way to make sure that the LEDs don't fall off the board, I will most likely create indentations where the LEDs will go
- Move the wires around so that they can't be seen



# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/Z8wsoRe9H5c" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Summary
For my main project, I am doing a LED scrolling message board. For my first milestone, I cut 6 strips of LEDs and attached them to a breadboard with an Arduino. I then found a starter code that I built off to perfectly match my LEDs and make them light up in the same pattern. 

### The different components of your project 

- WS2812B LED; An LED is a  light-emitting diode is a semiconductor device that emits light when current flows through it. Electrons in the semiconductor recombine with electron holes, releasing energy in the form of photons. The color of the light is determined by the energy required for electrons to cross the band gap of the semiconductor
- BreadBoard; A breadboard, solderless breadboard, or protoboard is a construction base used to build semi-permanent prototypes of electronic circuits. Unlike a perf board or stripboard, breadboards are reusable and do not require soldering or destruction of tracks.
- Arduino Nano; Arduino is an open-source hardware and software company, project, and user community that designs and manufactures single-board microcontrollers and microcontroller kits for building digital devices.
I attached the end of the LEDs to the power, ground, and control wires. I attached the power wires to the power rail on the breadboard, and the ground wires to the ground rail. Then attached a jumper wire from the power and ground rail to a 5-volt power source. I attached an Arduino Nano to the breadboard and connected jumper wires from the 5-volt pin and the ground pin to their perspective rails. I attached the control wires from the LEDs to the digital pins and installed a code to the Arduino Nano. 

## Progress

Currently, the LEDs and the Arduino are connected to a breadboard in the correct and all the LEDs light up but not in words. 

## Challenges 

On the LED strips, there are arrows, and those are in the direction that the electrical current flows. And I didn’t realize this so I was so confused about why my LEDs weren’t lighting up because I put all of the arrows facing towards the Arduino. After I realized this I cut my LEDs from the Arduino because it would be too much to desolder them and do all of that since I already put the wires in the heat tubes. So I moved my project onto a breadboard. 

## What your plan is to complete your project
  
For my second milestone, I have to write code for scrolling words and attach it to a perf board. 


# Starter Project

<iframe width="560" height="315" src="https://www.youtube.com/embed/gzErr8VK5Jg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For my starter project, I decided to make an alarm clock.   

## Project components and their purpose 

- Resistors- regulate the flow of electrical currents in an electrical circuit. They are also used to provide a certain amount of voltage for a transistor. The project required a certain number of Kohms in certain places, meaning it was used to give a certain amount of voltage. 
- Thermistor- In this project, this was used to determine the temperature outside
- Diode- directs the flow of electricity in a single direction, and can maintain a constant voltage and extract signals from video waves. 
- Photoresistor- senses when there is light or there is a light change. The photoresistor in this clock is used to determine the brightness of its surroundings and adjust the brightness of the clock display.
- Crystal oscillators oscillate at a particular frequency, which controls the timing of the circuit.  
- Passive Buzzer- It can play a variety of noises, in the clock it's used as an alarm

## Challenges

I faced many challenges as it was my first project. After I thought I was done with the whole project I realized that it was only showing the default display and I was not able to change the time or use any of the functions. But I troubleshot and I realized that most of the wires in the back were touching. Another problem came up for me, but I noticed the display was not really showing at all, and at first, I thought it was the photoresistor, but the battery just fell out.


# Schematics 
<!-- 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 
-->
# Code

```c++
#include <Adafruit_GFX.h>
#include <Adafruit_NeoMatrix.h>
#include <Adafruit_NeoPixel.h>
#ifndef PSTR
#define PSTR // Make Arduino Due happy
#endif
#define PIN 9

Adafruit_NeoMatrix matrix = Adafruit_NeoMatrix(64, 7, PIN,
  NEO_MATRIX_TOP     + NEO_MATRIX_LEFT +
  NEO_MATRIX_ROWS + NEO_MATRIX_ZIGZAG,
  NEO_GRB            + NEO_KHZ800);

const uint16_t colors[] = {
  matrix.Color(246, 161, 15), matrix.Color(0, 255, 0), matrix.Color(0, 0, 255) };

void setup() {
  matrix.begin();
  matrix.setTextWrap(false);
  matrix.setBrightness(40);
  matrix.setTextColor(colors[0]);
}

int x    = matrix.width();
int pass = 0;

void loop() {
  matrix.fillScreen(0);
  matrix.setCursor(x, 0);
  matrix.print(F("hello world"));
  if(--x < -70) {
    x = matrix.width();
    if(++pass >= 3) pass = 0;
    matrix.setTextColor(colors[pass]);
  }
  matrix.show();
  delay(70);
}

```

# Bill of Materials
<!-- 
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
-->

