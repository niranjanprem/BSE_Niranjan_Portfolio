# Text-to-speech

This project is a python-based text-to-speech document reader. It uses the Raspberry Pi and its camera to convert any images placed on the housing and reads it out loud with the speaker. The biggest challenge with this project was getting the camera to read properly. As it has no auto-focus feature, the lighting had to be very good for the code to be able to read text. I got over this struggle by making a better camera stand and increasing the natural lighting.

<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Niranjan Prem | California High School | Electrical Engineering | Incoming Junior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Image of the Engineer](image_link_here)

# Final Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/POlnQBgIE1E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Since my previous milestone, I was able to find a hilt for the camera that was stable, and the hardware aspect of the project is complete. I also converted the old command line code into the newer picamera2 database. One benefit of this change was that the camera preview was always available, enabling the user to set up the camera and make sure it is in focus/readable before clicking the button. Another problem that I stumbled upon was the camera rotation. The camera would be staring at the document it was supposed to read **flipped**, which meant that the Pi was reading an upside-down version of the text and would output gibberish. To solve this, I looked in the Raspberry Pi camera documentation and found a way to rotate the camera image 180 degrees. I also got rid of the breadboard entirely and soldered wires from the Pi to the LED and button to enable a more portable and robust design. After everything I've learned at BSE, I hope to create more projects using the Raspberry Pi and using my knowledge of soldering, and the experience I've gained with this hands-on learning style will help me in the future.

# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/NiRmhFbF8x4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Since my first milestone, I got the code to work and properly read text. I have also made lots of hardware improvements, including building the housing for the components. I wanted this document reader to be very portable, something that could be put in a backpack and transported from room to room. My solution to this was to hold the Raspberry Pi down into the housing with tape and cut outlines for the cables to be connected from the outside of the box. One challenge was finding a proper box for this project since I did not want to use wood. Some boxes were very big and caused the speaker to be muffled, and some boxes were too small to fit certain components in. In the end, I used a 4-inch high cardboard box and kept the speaker outside of the box. This made the speech a lot louder and more legible. Before my next milestone, I need to get a few things done, such as finishing the hilt for the camera.

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/Z37J3neOE3k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

My project is a text-to-speech reader in the Python language. To build the hardware aspect of this project, I used the Raspberry Pi camera and the breadboard. The breadboard electrically connects components like the LED and the button to allow them to integrate with the camera and code. Some technical progress I've made so far is connecting all the hardware components electrically and making sure the camera works. The next steps I want to take are to ditch the breadboard and move onto something more stable and presentable for maximum portability.

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resources to create professional schematic diagrams, though BSE recommends Tinkercad because it can be done easily and for free in the browser.

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here](https://www.markdownguide.org/extended-syntax/) to learn how to customize it to your project needs.

```python
# Your Python code here
