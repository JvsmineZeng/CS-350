# CS-350 - Project - Thermostat

### Summarize the project and what problem it was solving.
> SysTec asked us to create a smart thermostat prototype with the TI board. The board will act as a thermostat that will connect with WiFi. It will use the TMP006 temperature sensor to read the room's temperature using the I2C driver. The GPIO driver will be used to process outputs from the thermostat. This will be either an increase or decrease in temperature using the buttons on the TI board. The UART driver will simulate thermostat data being sent to the server. If the environmental temperature needs to change to meet the set temperature, the red light on the board will activate; if no change is needed, the green light will activate.

### What did you do particularly well?
> I did well designing the logic of this program. In the Module 5 milestone, I had trouble with the timer interrupt mechanism. After reviewing feedback from my professor, I realized I needed to elongate the time it took for the timer interrupts to be spaced out. I incorporated this into my program so it had time to process and display information in a readable format to the user. Using the flowchart helped me understand what variables were needed, and where the if-else and loop decisions needed to be in the program. 

### Where could you improve?
> I need to better familiarize myself with IDE setup when using external devices like the TI board. Sometimes, assignments would not compile because I forgot to incorporate certain dependencies and variables like the UART components in the final project. 

### What tools and/or resources are you adding to your support network?
> In future similar projects, I will refer to documentation for Code Composer Studio on the TI website (link here: https://www.ti.com/tool/CCSTUDIO). This will help me get a better understanding of the IDE and its components. It will also help me understand how the board communicates with my computer and the program I have written. I admit - these components were more difficult to work with than writing the program itself!

### What skills from this project will be particularly transferable to other projects and/or course work?
> Skills including working with state machines and embedded systems will help me in future projects. In other courses, I have learned different segments of the final project in this class. For example, I have learned how to write programs in a few introductory courses, design the user interface in my UI/UX design course, and create a project timeline in my Agile Development course. This course has helped me understand how the program is developed and passed onto the physical product itself. These skills help me gain a better understanding in full stack development for future projects, coursework, and job openings.

### How did you make this project maintainable, readable, and adaptable?
>  I referred to the CCS documentation and lab guides quite a bit. Fortunately, the lab guides provided a substantial amount of starter code. With the help of flowcharts, I was able to see where I would put certain decision branches and variables. I also made sure to incorporate concepts I learned from the ZyBooks modules in order for the thermostat to work. Every time I made substantial edits to the code, I made sure to check the environment settings, clean the code, and build the project before testing it in debug mode. I also made sure everything was indented and spaced nicely so I could keep track of my code and make it clear to the client who may review it.
