# Shift Overlapping
There are four cases of overlapping for two dates:

<img src="overlapping.png" />

And there are two cases of not overlapping:

<img src="no-overlapping.png" />

The following line represents not overlapping case:

## shift1.endTime <= shift2.startTime || shift1.startTime >= shift2.endTime

isOverlapping function returns the opposite.

<a href="https://lubana85.github.io/Shift-Overlapping/"> Example </a>

