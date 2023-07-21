# Text-to-speech

Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!

You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:
```HTML 
<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->
```

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Niranjan Prem | California High School | Electrical Engineering | Incoming Junior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="[https://youtu.be/NiRmhFbF8x4](https://www.youtube.com/embed/NiRmhFbF8x4")" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
  
For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

  Since my previous milestone, I was able to find a hilt for the camera that was stable and the hardware aspect of the project is complete. I also converted the old command line code into the newer picamera2 database. One benefit of this change was that the camera preview was always available, this enables the user to set up the camera and make sure it is in focus/readable before clicking the button. Another problem that I stumbled upon was the camera rotation. The camera would be staring at the document it was supposed to read **flipped**, which meant that the Pi was reading an upside-down version of the text and would output gibberish. To solve this, I looked in the raspberry pi camera documentation and found a way to rotate the camera image 180 degrees. I also got rid of the breadboard entirely, and soldered wires from the Pi to the LED and button to enable a more portable and robust design.



# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="[https://www.youtube.com/embed/y3VAmNlER5Y](https://youtu.be/NiRmhFbF8x4)" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Since my first milestone, I got the code to work and properly read text. I have also made lots of hardware improvements including building the housing for the components. I wanted this document reader to be very portable, something that could be put in a backpack and transported from room to room. My solution to this was to hold the raspberry pi down into the housing with tape and cut outlines for the cables to be connected from the outside of the box. One challenge was finding a proper box for this project since I did not want to use wood. Some boxes were very big and caused the speaker to be muffled and some boxes were too small to fit certain components in. In the end, I used a 4 inch high cardboard box and kept the speaker **outside**** of the box. This made the speech a lot louder and more legible. Before my next milestone, I need to get a few things done such as finishing the hilt for the camera, 

# First Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="[[https://www.youtube.com/embed/CaCazFBhYKs](https://youtu.be/Z37J3neOE3k)](https://youtu.be/Z37J3neOE3k)" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

My project is a text-to-speech reader in the python language. To build the hardware aspect of this project, I used the raspberry pi camera and the breadboard. The breadboard electrically connects components like the LED and the button to allow them to integrate with the camera and code. Some technical progress I've made so far is connecting all the hardware components electrically and making sure the camera works. The next steps I want to take is to ditch the breadboard and move onto something more stable and presentable for maximum portability.


# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
