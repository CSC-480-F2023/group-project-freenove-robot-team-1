# **Requirements and Constraints for Boundary Detection**



## **Functional Requirements**

While driving, the Freenove Smart Car shall detect boundaries using infrared scanning within ranges of 2 feet.

While driving, the Freenove Smart Car should not touch or move past the boundaries it detects.

When pushing a target, the Freenove Smart Car should stop interacting with the target once the exits the detected boundary.



## **Non-Functional Requirements**

When detecting a boundary, the Freenove Smart Car should be able to react to the boundary within less than 1 second.

The Freenove Smart Car should not require specialized calibration if it is to be distributed and scaled.



## **Technical Constraints**

If the Freenove Smart Car sees an object that infrared scanning does not work on, it will be unable to detect that object as a boundary.

If the Freenove Smart Car is unable to detect boundaries, it will be unreliable and disruptive when carrying out its objective.



## **Environmental Constraints**

If the Freenove Smart Car's infrared scanner malfunctions or is damaged, it might lose the ability to detect boundaries.




