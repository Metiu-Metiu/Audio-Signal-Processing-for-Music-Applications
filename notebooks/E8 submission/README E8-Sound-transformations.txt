You can find 2 Jupiter notebook files, which are the same apart from these differences, both concerning only part 2 of the assignment;

- E8-Sound-transformations_ProportionalTimeStretch

The time scaling has been implemented by PROPORTIONALLY STRETCHING the notes durations
Of the original sound

- E8-Sound-transformations

The time scaling has been implemented by ADDING an absolute time offset to the notes onsets of the original sound.


#############################

This assignment, to be, has been not much about creating a good-sounding sound,
But rather about creating a reusable, abstract and general purpose software system to transform sounds.
You can plug into it any other sounds.
Especially using sounds with the same F0 range, Between 430 hZ and 1000 hZ, you do not even need to change parameters for the HPS analysis.

About part 2, I imported and re-implemented a lot of code.
In order to quickly find the parameters you want to tweak in order to change the output sound at every code run (See "explanation"; I used constrained random numbers in order to generate a different sound every time the code is run, given that the minimum and maximum values for the ranges are not the same, that is, given that the range > 0), please just search the following string;

### define the transformations