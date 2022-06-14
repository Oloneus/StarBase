**Approach Setup**

set up in the following order !

Lever FcuBackward
> - LeverCenteringSpeed -->"**alr**"'

Lever FcuForward
> - LeverCenteringSpeed -->"**cruise**"'

Flight Control Unit
> - FCUGeneralMultiplier -->"**turtle**"'

MemoryChipt
> **Name** - **Value**
> - apd  ==  500 // Approach Ready Distance in Meters (200-999)
> - apt  ==  17  // Approach Target Distance in Meters (15-199) 
> - // Empty
> - akt  ==  3.6 //  (thrust diff) account for disparity in forward/rev thrust power
> - akp  ==  1.1  //  (proportional) how much we factor in our current distance (high distance = high thrust)
> - aki  ==  0.05  //  (integral) factor of how long we've been at our distance (the higher, the more aprupt thrust changes will be)
> - akd  ==  5  //  (derivative) factor of prediction of where we'll be in future (smooths the ride)
> - // Empty
> - apm  == // set by Script
> - ama  == // set by Script

Rangefinder
> - RangeFinderOnState --> "**arf**"
> - RangeFinderSearchLength == **1000**
> - RangeFinderDistance --> "**ar**"

Button
> **either**
> - Safety lid button (square) **or**
> - Safety lid button (round) **or**
> - Warning light button 12×12

> - ButtonState --> "**apr**"
> - ButtonOnStateValue == **1**
> - ButtonOffStateValue == **0**
> - ButtonStyle == **1**
> - ButtonColor --> "**apC**"
> - ButtonEnableBlink --> "**apw**"

Basic Yolol Chip
> - aSupportScript

Basic Yolol Chip
> - aApproachScript