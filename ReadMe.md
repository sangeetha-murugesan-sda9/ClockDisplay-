## Clock Display

## Introduction
The ClockDisplay class implements a digital clock display for a
European-style 24 hour clock. The clock shows hours and minutes. The
range of the clock is 00:00 (midnight) to 23:59 (one minute before
midnight).

The clock display receives "ticks" (via the timeTick method) every minute and 
reacts by incrementing the display. This is done in the usual clock
fashion: the hour increments when the minutes roll over to zero.

The NumberDisplay class represents a digital number display that can hold
values from zero to a given limit. The limit can be specified when creating
the display. The values range from zero (inclusive) to limit-1. If used,
for example, for the seconds on a digital clock, the limit would be 60,
resulting in display values from 0 to 59. When incremented, the display
automatically rolls over to zero when reaching the limit.

### Prerequisites
* BLUEJ 4.2.2.

## ScreenShots

## ClockDisplay

![ClockDisplat](ScreenShots/ClockDisplay.png)

## Create New Clock Display

![CreateNewClockDisplay](ScreenShots/CreateNewClockDisplay.png)

## Create New Number Display

![CreateNewNumberDisplay](ScreenShots/CreateNewNumberDisplay.png)

## Create Object Clock Display

![CreateObjectClockDisplay](ScreenShots/CreateObjectClockDisplay.png)

## Create Object Number Display

![CreateObjectNumberDisplay](ScreenShots/CreateObjectNumberDisplay.png)

## Functions of Clock Display

![FunctionsOfClockDisplay](ScreenShots/FunctionsOfClockDisplay.png)

## Functions of Number Display

![FunctionsOfNumberDisplay](ScreenShots/FunctionsOfNumberDisplay.png)

## Get Display Value (Number Display)

![GetDisplayValueNumberDisplay](ScreenShots/GetDisplayValueNumberDisplay.png)

## Get Time After Two TimeTick

![GetTimeAfterTwoTimeTick](ScreenShots/GetTimeAfterTwoTimeTick.png)

## Get Time (ClockDisplay)

![GetTimeClockDisplay](ScreenShots/GetTimeClockDisplay.png)

## Get Value After Incrementing Twice

![GetValueAfterIncrementingTwice](ScreenShots/GetValueAfterIncrementingTwice.png)


## Get Value (NumberDisplay)

![GetValueNumberDisplay](ScreenShots/GetValueNumberDisplay.png)

## Set Time (ClockDisplay)

![SetTimeClockDisplay](ScreenShots/SetTimeClockDisplay.png)

## Set Time (NumberDisplay)

![SetTimeNumberDisplay](ScreenShots/SetTimeNumberDisplay.png)