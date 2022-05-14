**Approach Setup**

set up in the following order !

Lever FcuForward
> - LeverCenteringSpeed -->"**cruise**"'

Flight Control Unit
> - FCUGeneralMultiplier -->"**turtle**"'

MemoryChipt
> **Name** - **Value**
> - apD  ==  200 // Approach Ready Distance in Meters (200-999)
> - apT  ==  17  // Approach Target Distance in Meters (15-199) 
> - aPg  ==  50  // set the maneuverability of the ship while approaching // Only on WorkerBee/GrumbleBee
> - aKt  ==  3.6 //  (thrust diff) account for disparity in forward/rev thrust power
> - aKp  ==  1.1  //  (proportional) how much we factor in our current distance (high distance = high thrust)
> - aKi  ==  0.05  //  (integral) factor of how long we've been at our distance (the higher, the more aprupt thrust changes will be)
> - aKd  ==  5  //  (derivative) factor of prediction of where we'll be in future (smooths the ride)
> - apM  == // set by Script
> - aR1  == // set by Script
> - aMa  == // set by Script

Rangefinder
> - RangeFinderOnState --> "**rF1**"
> - RangeFinderSearchLength == **1000**
> - RangeFinderDistance --> "**r1**"

Button
> **either**
> - Safety lid button (square) **or**
> - Safety lid button (round) **or**
> - Warning light button 12×12

> - ButtonState --> "**Apr**"
> - ButtonOnStateValue == **1**
> - ButtonOffStateValue == **0**
> - ButtonStyle == **1**
> - ButtonColor --> "**ApC**"
> - ButtonEnableBlink --> "**ApW**"

Basic Yolol Chip
> - aSupportScript

Basic Yolol Chip
> - aApproachScript
