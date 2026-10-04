# Initial Capstone Reading and Planning Reflection

**Student:** Justin Marsalek
**Date:** October 2, 2026
**Repository Status:** Early individual planning; project concept and partnership are not final

---

## 1. My Understanding of the Challenge

The goal of the EDD capstone is to design, build, test, demonstrate, and document a working device controlled by a digital control system. Examples include an Arduino, Raspberry Pi, or another approved digital controller. A VEX V5 brain cannot be used.

The project needs to include functioning elements in all five required categories: **Output Display, Manual User Input, Automatic Sensor, Actuators/Mechanisms/Hardware, and Logic/Processing/Control**. The important part is that these elements are integrated into one useful system rather than simply being separate components that happen to work individually. The device needs to perform its intended function reliably and repeatedly.

A strong project should also demonstrate meaningful engineering work. The project should involve research, design decisions, testing, troubleshooting, and improvements. If I use code or circuits from another source, I need to understand how they work, add value through my own implementation, and cite those sources.

The final project also needs to be safely constructed, presentable, and properly documented. The final GitHub submission will include information such as the design summary, system details, evaluation, parts list, lessons learned, construction instructions, wiring diagrams, CAD files when applicable, and well-commented code.

---

## 2. Requirements and Constraints

### Control System

The device must be controlled by one or more digital control systems. Examples given in the instructions include Arduino, Raspberry Pi, ESP8266, and DIP logic gates. A VEX V5 brain is specifically not allowed.

### Five Functional-Element Categories

The project must include all five categories:

1. **Output Display**

   * LEDs, seven-segment displays, LCDs, screens, or another useful output.

2. **Manual User Input**

   * Buttons, switches, potentiometers, joysticks, keypads, keyboards, or touchscreens.

3. **Automatic Sensor**

   * Proximity, distance, temperature, sound, accelerometer, encoder, or another appropriate sensor.

4. **Actuators, Mechanisms, and Hardware**

   * Motors, servos, stepper motors, or useful mechanical hardware and mechanisms.

5. **Logic, Processing, and Control**

   * Programmed logic, calculations, data storage, integrated circuits, or other processing and control.

The five categories need to work together as part of the same device. A component that is simply connected but does not contribute to the system would not be useful.

### Materials and Cost

The project can use normal materials and approved components available in the lab. The project has a limit of **250 g of PETG or PLA filament**, including prototypes. There is also a limit of **$20 in pre-approved student-purchased parts per project**.

I need to avoid buying expensive or unnecessary components. The controller and other components should be selected based on what the project actually requires.

### Integration and Reliability

The device needs to operate as a complete system. The sensor should affect the program, the program should control the outputs or mechanisms, and the user should be able to interact with the device.

The project also needs to be repeatable. A system that works once but fails frequently would not demonstrate a successful final design.

### Safety, Construction, and Appearance

The device should have secure wiring and connections, appropriate power, sturdy construction, and safe moving parts. I need to avoid exposed hazards, pinch points, weak mechanisms, and messy wiring.

The appearance also matters. The project should look like a prototype of a potential finished product rather than a collection of loose components.

### Milestones and Deliverables

The project includes several major checkpoints and deliverables, including the initial proposal, status checks, initial systems demonstration, documentation setup, engineering notebook, poster presentation, GitHub engineering report, and final project demonstration.

The GitHub report will need a README, design summary, system details, design evaluation, parts list, lessons learned, construction instructions, wiring diagrams, CAD files when applicable, and well-commented code.

### Sources and Documentation

Any code or circuits taken from outside sources must be understood and cited. I also need to document my own design process, testing, failures, changes, and decisions throughout the project.

---

## 3. Personal Readiness

### Skills and Resources I Already Have

* I have experience programming a Raspberry Pi using Python.
* I have experience using GPIO inputs and outputs such as buttons and LEDs.
* I have worked with state-based programming and systems where inputs change outputs.
* I have experience with VEX V5 engineering and mechanical construction.
* I have experience troubleshooting wiring and hardware problems.
* I have experience using GitHub for engineering projects.
* I have experience keeping an engineering notebook and documenting project work.

### Skills I May Need to Learn or Improve

* **Sensor integration:** I may need to learn how to reliably read and interpret a new type of sensor.
* **Mechanical mechanisms:** I may need more practice designing mechanisms that move smoothly and consistently.
* **CAD and 3D printing:** I need to design useful parts while staying under the filament limit.
* **System integration:** I need to make sure all five functional categories work together.
* **Testing:** I need to improve at designing repeatable tests and using results to make design changes.
* **Documentation:** I need to consistently record failures, improvements, and design decisions instead of waiting until the end.

---

## 4. Three Possible Directions

|                                     | **Idea 1: Smart Pet Feeder**                                                  | **Idea 2: Smart Recycling Sorter**                                                               | **Idea 3: Smart Parking Assistant**                                                     |
| ----------------------------------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------- |
| **Idea / User / Problem**           | Automated feeder that dispenses a controlled portion for a pet.               | Small automated system that detects an object and directs it toward an appropriate sorting area. | Small-scale system that detects a model vehicle and assists with parking.               |
| **Output / Display**                | LEDs or LCD showing Ready, Dispensing, and Complete.                          | LEDs or LCD showing object/status and sorting result.                                            | LEDs or LCD showing available/occupied or distance information.                         |
| **Manual User Input**               | Buttons to start, cancel, or select a feeding cycle.                          | Button to start or reset the sorting cycle.                                                      | Button to start or reset the system.                                                    |
| **Automatic Sensor**                | Limit/proximity sensor to confirm mechanism position.                         | Sensors to detect object presence or characteristics.                                            | Distance sensor to detect the vehicle's position.                                       |
| **Actuator / Mechanism / Hardware** | Servo-powered rotating food dispenser.                                        | Servo-controlled gate or diverter.                                                               | Servo-controlled parking barrier.                                                       |
| **Logic / Processing / Control**    | Controller reads buttons and sensor, operates servo, and completes the cycle. | Controller processes sensor data, determines the sorting action, and controls the servo.         | Controller processes distance readings, controls the display, and operates the barrier. |
| **Biggest Risk / Unknown**          | Getting consistent portions without the mechanism jamming.                    | Accurately detecting objects while keeping the mechanism simple and reliable.                    | Getting consistent distance readings and responses.                                     |

### Idea 1: Smart Automatic Pet Feeder

This project would automate the process of dispensing a controlled amount of food. It would combine user input, sensing, programming, and a servo mechanism. The main challenge would be making the dispensing mechanism reliable enough to release consistent portions without getting stuck.

### Idea 2: Smart Recycling Sorter

This project would use sensors and programmed logic to detect an object and then use a motorized mechanism to direct it to a specific area. It would provide a strong opportunity to integrate sensing, programming, mechanical design, and user interaction.

### Idea 3: Smart Parking Assistant

This project would use a distance sensor to detect the position of a model vehicle. The controller could use the sensor information to provide feedback through LEDs or an LCD and control a small servo-powered barrier. The main concern would be getting consistent sensor readings.

---

## 5. Current Front-Runner

My current front-runner is the **Smart Automatic Pet Feeder**.

This concept has strong potential because it naturally combines all five required categories into one system. The user provides an input, sensors collect information automatically, the controller processes that information, the display communicates the system's status, and the motorized mechanism dispenses the food.

The project also has a clear purpose and gives me opportunities for meaningful research. I would need to investigate sensors, dispensing mechanisms, servo motors, portion control, programming logic, and reliability testing. This would allow me to develop the project rather than simply copy an existing design.

The project could also stay within the material limits if I keep the design compact and use components already available in the lab. The 250 g filament and $20 purchased-part limits make it important to avoid unnecessary parts and keep the mechanism simple.

The biggest concern is reliability. If the dispenser releases too much food, too little food, or gets stuck, the system would not work as intended. I may need to test multiple dispensing mechanisms and simplify the design if necessary. A smaller feeder that consistently dispenses the correct amount would be more valuable than an overly complicated project that is unreliable.

---

## 6. Anticipated Challenges

### Challenge 1: Mechanical Construction

**Why it matters:**
The sorting mechanism needs to move consistently. A gate that jams or does not return to the correct position could cause the entire system to fail.

**Possible preparation or test:**
Build a simple prototype of the gate and repeatedly test the servo movement before designing the final mechanism.

### Challenge 2: Sensor Reliability

**Why it matters:**
The controller will make decisions based on sensor information. Incorrect or inconsistent readings could cause the system to sort objects incorrectly.

**Possible preparation or test:**
Test possible sensors independently and record repeated readings under the same conditions. Determine whether thresholds or filtering are needed.

### Challenge 3: Electronics and Programming Integration

**Why it matters:**
The sensor, buttons, display, controller, and servo all need to communicate correctly. A problem in one part could affect the entire system.

**Possible preparation or test:**
Build the project in stages. Test the sensor first, then the input and display, then the actuator, and finally combine everything.

### Challenge 4: Time and Cost

**Why it matters:**
The project has limits on both time and materials. An overly complicated design could require too many prototypes or expensive components.

**Possible preparation or test:**
Create a preliminary parts list and system diagram before beginning construction. Estimate cost and filament use before creating the final design.

### Challenge 5: Reliability and Safety

**Why it matters:**
The final device needs to work consistently and safely during the demonstration.

**Possible preparation or test:**
Perform repeated complete-system tests and inspect wiring and moving mechanisms regularly. Record failures and correct them before the final demonstration.

---

## 7. Individual or Partner Project

At this point, I am leaning toward working with a partner, but I am not making a final decision yet.

If I work with someone else, reliability and communication will be important. I would want a partner who completes assigned work, communicates when there is a problem, and contributes consistently. I would not choose a partner only because they are a friend.

Complementary skills would also be useful. For example, one person could have stronger mechanical or CAD skills while the other has stronger programming or electronics skills. However, both people should understand the overall system and be able to contribute to testing and documentation.

If I cannot find a reliable partner, I would consider working individually rather than having an unreliable partnership create problems with the project.

---

## 8. Questions and Clarifications

1. Which sensors, motors, controllers, and other components will be available in the lab for the capstone?

2. How will the 250 g filament limit be measured when failed prototypes and test prints are included?

3. Which student-purchased components require pre-approval?

4. How much existing code can be used if it is understood, modified, and properly cited?

5. For the early bird requirement, do all five functional categories need to be integrated into the same physical prototype?

6. If testing shows that my original concept is impractical, how late can I change the project concept?

7. Are there any specific restrictions on what objects can be used to test an automated sorting system?

8. Are the dates in the current instruction document expected to remain the same for next semester?

---

## 9. Preparation Plan

1. **Research the three project concepts** and compare their costs, complexity, available components, and major risks.

2. **Check available lab components** to determine which sensors, motors, displays, and controllers could be used without purchasing unnecessary parts.

3. **Research possible sensors** for the recycling sorter and determine what information they can realistically provide.

4. **Create a preliminary system diagram** showing the controller, manual input, sensors, display, actuator, and mechanical mechanism.

5. **Build a sensor test circuit** to determine whether a potential sensor provides consistent readings.

6. **Prototype a servo-controlled gate** and test whether it can repeatedly move between positions without jamming.

7. **Create a basic software test** that reads an input, processes sensor information, and controls an actuator.

8. **Estimate the project's cost and filament use** before beginning the final design.

9. **Research existing automated sorting mechanisms** for ideas while documenting the sources that influenced my design.

10. **Decide whether to work individually or with a partner** based on reliability, communication, skills, and expected workload.

---

## 10. Final Takeaway

The most important principle I need to remember is that the capstone should be **one integrated and reliable system rather than a collection of separate components**.

It would be easy to add a button, sensor, LED, motor, and controller just to satisfy the five categories. However, the project is supposed to demonstrate engineering through integration, useful functionality, research, testing, and improvement.

I should therefore choose a project that is challenging enough to demonstrate engineering skills but realistic enough to finish and make reliable. I also need to consider cost, materials, safety, time, and the amount of research required before committing to a final design.

My current goal is not to make the most complicated project possible. My goal is to create a device where every major component has a purpose and where the hardware, software, sensing, and mechanical systems work together reliably.

---

## Assistance Acknowledgment

I used permitted AI assistance to help organize my understanding of the capstone instructions, brainstorm possible project concepts, and draft this initial planning reflection. I reviewed the assignment requirements and used them to guide my planning. Any final project decisions, construction, testing, programming, and documentation will be reviewed and developed by me.
