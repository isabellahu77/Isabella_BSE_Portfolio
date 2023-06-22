# Isabella BSE Portfolio
<!-- Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails! -->

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Isabella H | Homestead | Electrical Engineering | Incoming Junior

<!--**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.** -->

<!-- ![Headstone Image](Isabella-Headshot.png) -->
<img src="Isabella-Headshot.png" width="215" height="300">
  
# Final Milestone
<!-- For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> -->

# Second Milestone
<!-- For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> -->

# First Milestone
My project is a solar tracker, which tracks where there is the most light, as well as tracking the temperature and humidity of the air. In the first milestone, I finished building the entire project, as well as the coding portion of 9 projects (kit comes with 11 total projects). Each individual part works and have been tested, and are mostly combined in the last project. I have yet to figure out the code for determining where the solar panel turns based off the light that is projected onto the tracker. A problem I was currently facing was with the connection of a pair of the wires, because I plugged one of them into the wrong socket, which resulted in a short circuit and damaged the sensor I was working with. The solar panel does not move very smoothly, and I plan to figure out what is causing that, as well as implement the actual movement for the panel before my next milestone. For what’s next, I plan to continue working on the coding for this project and put back the lithium power module, as well as understand more about the different processes and how different parts work. 

## Summary:
- Solar Tracker, measures solar energy, temperature, and humidity
- completed build process, as well as most of Arduino coding portion (9 of 11 proj)
- struggled with connecting pair of wires, code for movement of servos

### Components: 
- photoresister sensor: changes its resistance when light shines on it
- humidity and temperature sensor: detects and measures dampness and air temperature
- passive buzzer: plays variety of tones that could be modified
- digital intensity module: digital light intensity sensor integrated circuit used for two-wire serial bus interface
- solar panel, push button module, display module, control board, led module

<!-- **Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.** -->

<iframe width="560" height="315" src="https://www.youtube.com/embed/uOYtJBz5YxU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Starter Project
My starter project was the Useless Box, which is a box that turns itself off when you switch it on. It has a set of switches, a circuit board (PCB), a small motor, a LED, an arm, and the box itself. When the switch is turned on, the lid of the box will open due to the arm raising, and the arm will turn off the switch. This project consists of the process of soldering components like resistors, switches, and an LED to the circuit board, and screwing in screws to connect the motor and board to the main box. When you turn the switch, the motor gains power due to the completion of the circuit so it starts rotating, which turns on the LED and moves the arm inside the box to turn the switch off which cuts the circuit and thus makes the motor stop running. There were a few parts in my kit that arrived a bit off center, which caused me to struggle towards the end with putting together the box because I had to sand down a few pieces and the acrylic panels ended up snapping due to how brittle it was, but after switching out the pieces I was able to get the project running.

## Summary:
- Usless Box, turns itself off when you turn switch on
- when switch on, motor turns on which causes arm to turn and turns off switch
- struggled with soldering at first, acrylic panels were off center and brittle

### Challenges Faced
- putting together box, sanding down pieces and replacing them
- soldering on circuit board (PCB)

<iframe width="560" height="315" src="https://www.youtube.com/embed/ec8RczE3qd8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Schematics 
<!-- Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. -->

# Code
<!-- Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
``` -->

# Bill of Materials
<!-- Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:| -->

# Other Resources/Examples
<!-- One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here. -->

