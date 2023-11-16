# Requirements for Ball and Object Detection

## Functional Requirements 
The Freenode Smart Car shall detect balls or objects in one of three possible ways.
1. When a ball is detected within one foot of the car, the car shall determine.
2. When the car is given the color of a ball, it must determine the location.
3. When the car detects objects found within its object models it shall determine which object it is.

## Non-Functional Requirements
The car should be able to determine the color of a detected ball in less than one second.
The car should be able to determine the location of a ball in less than five seconds.
The car should be able to determine what a detected object is in less than one second.

## Stakeholder Persona - Sir Thorsday (Professional Robot Enthusiast)
### Job summary
Sir Thorsday is responsible for evaluating the car's abilities and performance at the request of an unknown entity *(Definitely not Professor Munday)*. He ensures that the car can perform its tasks correctly and in a timely manner.

### Motivations
He has been paid by the unknown entity to determine if the car can correctly do the following: 
- detect balls and their color
- find a ball given its color
- determine what an object is.
#Frustrations
He will report the robot to the unknown entity if any of the following happens
- The car fails to detect a ball within one foot of the car.
- The car misidentifies the color of a ball.
- The car fails to determine the color of the ball in less than one second.
- The car fails to find a ball of a particular color.
- The car fails to find a ball in less than five seconds.
- The car misidentifies an object.
- The car fails to identity an object in less than one second.
