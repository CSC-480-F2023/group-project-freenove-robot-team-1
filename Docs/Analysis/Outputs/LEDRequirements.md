# **Requirements and Constraints for Boundary Detection**



## **Functional Requirements**
We shall create a three class YOLO object model of approximately 150-200 images taken from various backgrounds and angles.

While driving, the Smart Car shall not move past the provided boundary lines of the course.

While driving, the Smart Car shall avoid objects within the provided boundary course.

When objects found in its object model, the Smart Car shall flash LEDs in a pattern, drive towards detected object and stop within one to two feet away from object, flash the LEDs indicating movement towards object has been completed, and pause program from five seconds before continuing onto next object.

## **Non-Functional Requirements**

When dececting an object, the Smart Car shall be able to distinguish between the color of the object and flash that color LED.


## **Technical Constraints**

If the Smart Car is not able to detect a object, it will be unable to complete the reuirements.



## **Stakeholders**

### **User**
The user of the Smart Car will be the team or individual that will use the car for either competition or as a hobbie.
### **Acquirer**
The acquirer of the Smart Car will be the team or individual that will use the car for either competition or as a hobbie.
### **Producer**
The producer of the Smart Car are the Software Engineering students to help with the project.
### **Regulator**
The Regulators for the Smart Car is Dr.Munday.

## Stakeholder Persona - Team Freenove Robot 1 (Group designing the software)
### Job Summary
Team Freenove Robot 1 are the Software Engineering students responsible for designing, developing, and delivering the Smart Car system

### Motivations
They have been tasked by Professor Munday to determine if the car can correctly do the following: 
- Create a three-class YOLO object model based on 150-200 images from various backgrounds and angles.
- Implement the functionality for the Smart Car to flash LEDs in response to detected objects and move towards them
- Stop within a specific distance of the detected object
- Indicate completion of the movement towards the object.

### Frustrations
They will report the robot to Professor Munday if any of the following happens:
- The car fails to detect a YOLO object that is within one foot of the car
- The car fails to stay within the given boundry
- The car misidentifies the color of the object, and flashes wrong color LED
- The car fails to find a object of a particular color
- Lack of effective communication among team members or with stakeholders, including Dr. Munday as the regulator
- Fails to meet the requirements and expectations of both users and acquirers.
