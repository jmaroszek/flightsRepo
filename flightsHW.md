Flights and Departure Delays
================
Jonah Maroszek
2/19/2021

# Introduction

I chose to examine how precipitation, age of the plane, and destination
would affect the average departure delay. In summary:

  - Precipitation and departure delay does not follow a linear
    relationship as I would have expected, but in general more
    precipitation results in a greater departure delay.  
  - The age of the plane and departure delay are positively related up
    until 10 years, and then negatively related until the planes are
    taken out of commission. This also goes against what I would have
    expected.  
  - NEVER fly to Oklahoma (unless you want to experience long delays)

### Impact of Precipitation on Average Delay

I expected there to be clear linear relationship between the amount of
precipitation and the average delay. It appears that this relationship
does not hold in general, as there are oscillations. However, as a rough
estimate, lower precipitation typically results in a shorter departure
delay ![](flightsHW_files/figure-gfm/Weather-1.png)<!-- -->

### Impact of Age of Plane on Average Delay

There is an inverted U shape when you plot average departure delay
versus the age of the plane, with the peak occuring at around 10 years.
This also defies my expectation. It looks like if you want to experience
the lowest delay, you should fly on either a very young or very old
plane. The trend could reverse at around 10 years because the airlines
keep a closer eye on the possible mechanical issues that could cause
delays, and either remove them from service or make sure there is enough
time to fix them.  
![](flightsHW_files/figure-gfm/Age%20of%20Plane-1.png)<!-- -->

### Impact of Destination on Average Delay

If you are flying to a city designated by a dark purple circle, you
should expect a higher average delay than the lighter color cities.
![](flightsHW_files/figure-gfm/Destination%20Delay-1.png)<!-- -->
