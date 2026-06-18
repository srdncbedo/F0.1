# F0.1
A little aerodynamic toy car born to be upcycled from an empty deodorant can, obliged to be 3D printed. It can be controlled by your phone using dabble!

<img width="756" height="406" alt="f01_render" src="https://github.com/user-attachments/assets/67c6436e-8705-46cd-bc46-1829a34098a9" />

# Key Features
- Can be controlled using bluetooth and the app dabble.(check code/compilation instructions for how to use)
- Uses a good mechanism of a linear and spur gear for steering.
- The microcontroller used is ESP32 which performs good enough in bluetooth data transfer with its built in bluetoth and is quite affordable.
- It is expected to have a speed of 2.8 km/h with its 500 rpm dc motors with gear reduction.
- The steering mechanism uses a 50 rpm dc motor with increased torque.
- The power source used is a 9v battery.
- A battery lid is designed for easier exchange.
- TB6612FNG motor drivers are used for a better performance from dc motors.
- Its approximately 30 cm in length and 11 cm in width.

# CAD and Assembly
- For assembly; screws, nuts and heat set inserts are used.
- Most of the parts are held in place by chassis
- Look at CAD/General Explanation for more details. 
# Wirings

Made using KiCAD. A 3.3v voltage regulator is used at the voltage in pin of the esp32 and the same voltage is given to driver motors logic pins. To increase the safety of components suitable capacitors are used at both end of the regulator. 

<img width="909" height="855" alt="image" src="https://github.com/user-attachments/assets/f62855bf-8c70-44b6-8970-d6faa65cb9a4" />
If more detail is needed the schematic document itself is also uploaded.

# Story and Purpose

After the technical details I would like to share my story of building this project as well. One night I was sitting on my desk just overthinking and doing nothing as usual. Saw my deodorant can, it was empty and thought why not build something with it and the idea of building a decorative F1 car came to my mind. I just ran into our schools workshop and started cutting some parts from paper. I just sticked them to the deodorant can's surface which I straightened before cutting the papers. After sticking them I just cut all the parts with dremel and sticked them together with glue. After 3 days of after school work this freak was what I got(it doesnt even look decorative tho):

<img width="2313" height="1094" alt="519a8954-5b14-4624-a40c-94fdf66333a9" src="https://github.com/user-attachments/assets/eab0a45a-51b8-44d1-bcc0-36026e4bfa59" />


After this bad start I just imagined some better stuff and decided to build something better: An F1 car with remote control using bluetooth and dabble.  Even though this direct building part wasn't a good start, after several attempts of designing I managed to get the complete design to be 3D printed:
<img width="1920" height="1080" alt="V1" src="https://github.com/user-attachments/assets/d1a82697-cdcb-4c5f-926a-575901fb2a4e" />

After the project is finished I am thinking about giving it to my 8 years old cousin as a gift. So the projects purpose can be concluded as making children and F1 lovers (like me) happy!
# Credits
This project uses:
- Fusion 360
- KiCAD
- Arduino IDE
- Macondo Hack Club
