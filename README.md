# ChempInput
Input system for Chemp Physics Modding

Chemp Input Functions
Floats
leftTriggerFloat - returns the left hand's trigger float (0.0 to 1.0)
 rightTriggerFloat - returns the right hand's trigger float (0.0 to 1.0)
 leftGripFloat - returns the left hand's grip float (0.0 to 1.0)
 rightGripFloat - returns the right hand's grip float (0.0 to 1.0)
Bools
leftTriggerDown - returns true if left trigger pressed beyond 0.8 threshold
 rightTriggerDown - returns true if right trigger pressed beyond 0.8 threshold
 leftGripDown - returns true if left grip pressed beyond 0.8 threshold
 rightGripDown - returns true if right grip pressed beyond 0.8 threshold
leftPrimaryDown - returns true if left hand primary button is pressed
 rightPrimaryDown - returns true if right hand primary button is pressed
 leftSecondaryDown - returns true if left hand secondary button is pressed
 rightSecondaryDown - returns true if right hand secondary button is pressed
leftThumbstickDown - returns true if left hand thumbstick (primary 2D axis) is clicked
 rightThumbstickDown - returns true if right hand thumbstick (secondary 2D axis) is clicked
menuButtonDown - returns true if the menu button on the left hand is pressed
Vectors
leftThumbstickVector - returns the Vector2 value of left hand thumbstick (primary 2D axis)
 rightThumbstickVector - returns the Vector2 value of right hand thumbstick (secondary 2D axis)

