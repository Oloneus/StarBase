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
> - apD  ==  200 // Approach Ready Distance in Meters (200-999)
> - apT  ==  19  // Approach Target Distance in Meters (15-199) 
> - aTl  ==  35  // set turtle factor of the ship (20-100)
> - aPg  ==  50  // set the maneuverability of the ship while approaching // Only on WorkerBee/GrumbleBee
> - aKt  ==  2.25 //  (thrust diff)   account for disparity in forward/rev thrust power
> - aKp  ==  1.5  //  (proportional) how much we factor in our current distance
> - aKi  ==  0.01  //  (integral)     factor of how long we've been at our distance
> - aKd  ==  4  //  (derivative)   factor of prediction of where we'll be in future
> - apM  == // set by Script
> - aR1  == // set by Script

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