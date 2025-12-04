# SmartDogDoor-AI
The goal of this project is to create an AI-powered smart dog door system that identifies a dog using a webcam and a trained machine learning model. When the AI detects a dog, it sends a signal to an Arduino, which updates a 1602 LCD display to change from “Locked” to “Unlocked.”

Category |Item                           | Version         | Hidden Detail                                                                  |
---------------------------------------------------------------------------------------------------------------------------------------------
Software |Python                         |3.10             |                                                                                |
         |TenserFlow                     |2.10             |                                                                                |
         |NumPy                          |                 |                                                                                |
         |OpenCV                         |4.12             |                                                                                |
         |pip                            |                 |                                                                                |
         |VSCode                         |                 |                                                                                |
         |Arduino IDE                    |Latest           |                                                                                |   

Hardware| Arduino Uno                    |                  |Must match correct COM port                                                    |
	      |USB cable                       |                  |Faulty cables cause “Serial not found” errors                                  |
	      |1602 LCD with I2C or pin header |With header       |	Pins must match wiring exactly; contrast knob must be adjusted to see text    |
	      |Breadboard                      |Full or half-size |	Must firmly seat LCD + wires                                                  |
	      |Jumper wires                  	 |Male-to-male      |	Loose wires = LCD shows blank screen                                          |
	      |External webcam                 |                  |                                                                               |
	      |5V power from Arduino           |		              |LCD will not turn on without 5V + GND                                          |


