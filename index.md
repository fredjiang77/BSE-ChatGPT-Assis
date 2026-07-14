# ChatGPT AI Assist
The project that I am making is a Ras-pi ChatGPT Assistant. This uses the Raspberry Pi computer and using it to create a voice-enabled ChatGPT interface that allowed me to speak to it and generate spoken responses. 

| **Name** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Frederick J | Appleby College | Electrical Engineering | Incoming Senior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/RjnOawhe9nk?si=F7XG3wbCmmwDfKaE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

# First Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/RjnOawhe9nk?si=F7XG3wbCmmwDfKaE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For my first milestone, I intend on finishing my hardware and raspberry pi setup. I plan to build a AI assistant in which I could talk to it and get responses back. I will have a raspberry pi as the big computer, a usb mic to recieve audio, a usb speaker to emmit audio, and a breadboard and switch to turn the assistant into listening mode. I finished setting all of this up as well as most of the software needed for the assistant to work. In the video, I demonstrated that my ai assistant could listen to me and replay what I have said. Some challenges that i faced along the way was that the SSH didn't work for a long time. I couldn't get the raspi to connect with the external device for a long time, and had to reflash more than ten times. I am still dealing with some issues with the mic and it is not picking up any audio on startup. My plan is to fix those issues I am am pretty much done with my base project.

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
| Raspberry Pi | Used for being the computer of the project  | $95.19 | <a href="https://www.amazon.com/RasTech-Raspberry-Starter-Heatsink-Screwdriver/dp/B0C8LV6VNZ/"> Link </a> |
| USB Mic | Capture voice commands | $7.56 | <a href="https://www.amazon.com/dp/B01MQ2AA0X?ref=fed_asin_title"> Link </a> |
| Speaker | Emmit Audio | $13.99 | <a href="https://www.amazon.com/Mobile-Speaker-Compact-Adhesive-Installation/dp/B0D95ZYCW6/"> Link </a> |
| Screwdriver Set | Screw Screws | $5.94 | <a href="https://www.amazon.com/Small-Screwdriver-Set-Mini-Magnetic/dp/B08RYXKJW9/"> Link </a> |
| Screen | Monitor  | $48.95 | <a href="https://www.amazon.ca/Freenove-Touchscreen-Raspberry-Capacitive-Driver-Free/dp/B0B455LDKH/ref=sr_1_2_sspa?crid=OQBCOAOP88TL&dib=eyJ2IjoiMSJ9.1ZP-x4GHf2bcWw7fBBlvjsT46rIXAvkE0H331aIl8FAkbJRCKhd-pnI2ZwOvSuPL4RtzPlki5UYA2eBSsEo6HbXBlhEborLKIdEWTiPTTLzerCnh0nYP0_TbflmFj_9G0oJsPQLkCe6PS5d78qHZLwLDx-QDT_gnI7qF3nRlsQi_Vm8kU9NkXcM5BbxOUGaKpLOmknhEjMpyXurIq_l_lwxLLQ98JvOVTneIahAxS_o2jWDGE4F0YbOcVTdbTTgtt-ohDw8otjMbSnlluE57aqdHoldDx12L3zrxyLXk3lE.nrTatiTA204s0YHM-0JkqKNkzsKVabb3qkPt71vNq-k&dib_tag=se&keywords=raspi%2Btouch%2Bscreen&qid=1783696509&sprefix=raspi%2Bscreen%2B%2Caps%2C107&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1"> Link </a> |


# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Instructables Original Project](https://www.instructables.com/Customizes-a-ChatGPT-Assistant-Using-a-RaspberryPi/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
