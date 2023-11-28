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




# **User Stakeholder Persona: Boris Satrick (Local Sumo Bot Host)**

## **Job Summary**
Boris is hosting an upcoming event where entrants will compete against AI sumo bots with their own sumo bots. He is reaching out to nearby AI vehicle producers to find the product best fit for his event.

## **Motivations**
Boris is going to prioritize the product choice off of which one performs these functions the best:
- Detecting and avoiding contact with the given barrier while moving within it.
- Detecting other bots within the given barrier and effectively navigating to them.
- Attempting to push detected bots until they are no longer in the barrier.


## **Frustrations**
Boris will have a significantly decreased chance to choose a  product if it runs into one or more of the following incidents at any point during testing:
- Moving past the barrier on its own.
- Ignoring bots within detection range.
- Stopping movement randomly or getting stuck when a clear out is present.



