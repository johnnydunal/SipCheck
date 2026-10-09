# Update: The great pivot!
After spending a while researching and planning out the design for the smart coaster, I've realized that while it's a cool concept, what I really need is something a bit more useful and powerful with a greater range of capabilities. So I've decided to pivot the project! I've now decided to build a smart desk command center that displays information such as time, weather, and calendar events using an E-paper display and also has a built-in AI-powered voice assistant!

I'll be using a similar architecture to the previous project, including an ESP-32 controller, but now adding an E-Paper display, microphone/speaker, and temperature/humidity sensor. The coaster project helped me understand and learn how PCB's function and are designed, so I can now carry those skills over to this project!

I also generated some concept art for how I want this to look:

![Concept art for the smart desk hub.](https://halflife.hackclub-assets.com/hackclub-half-life/sessions/KvD7dTJaHVfjYIigORhVQkYxq5FrUFSP/c7db96425b23dde9a4073f139bb3a585a13c03bfefbb66391b9a93df28627149.jpg)

Anyways, I'm now working on planning and designing the PCB board for this new project:

![The beginnings of the PCB design for the smart desk hub.](https://halflife.hackclub-assets.com/hackclub-half-life/sessions/KvD7dTJaHVfjYIigORhVQkYxq5FrUFSP/05f5caeddaaebf72280a5da88365c8a52838798ed09a1d0af46319bc03e8a4c3.png)

I'm planning to also use a Raspberry Pi 4 board to allow fast and efficient audio to text conversion for the ai voice assistant, and the ESP32 for controlling the display, connecting to APIs, calculating the time, or reading sensor data.