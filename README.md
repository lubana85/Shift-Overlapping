# Shift Overlapping
Determining if Two Date Ranges Overlap

## There are four cases of overlapping for two dates:

<img src="overlapping.png" />

## And there are two cases of not overlapping:

<img src="no-overlapping.png" />

The following line represents not overlapping case:

## shift1.endTime <= shift2.startTime || shift1.startTime >= shift2.endTime

isOverlapping function returns the opposite.

The following example validates the entered dates first to check that:
* shift1.startTime < shift1.endTime AND
* shift2.startTime < shift2.endTime
before executing isOverlapping function:

<a href="https://lubana85.github.io/Shift-Overlapping/"> Example </a>

