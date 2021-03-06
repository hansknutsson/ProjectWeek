Back to [Projects List](../../README.md#ProjectsList)

# [SlicerAstro](https://github.com/Punzo/SlicerAstro) Update
<img src="https://raw.githubusercontent.com/Punzo/SlicerAstroWikiImages/master/SlicerAstroIcon.png" width="150" height="150">

## Key Investigators
<img src="https://www.davidepunzo.com/assets/images/DPLogo.png" width="150" height="150">
- [Davide Punzo][punzo] ([Freelancer][punzodavide])


## Description

A list of bugs to fix (and enhancement to do) to update SlicerAstro
to the current version of 3DSlicer is reported in SlicerAstro issue [106][slicerastroissue].

## Objective

Address SlicerAstro issue [106][slicerastroissue]:

- Fix packing of astropy and scipy

- Fix Contours (in binary segmentation) in the modules AstroVolume, AstroSmoothing and AstroModeling.

- Fix Histogram in Astrovolume when changing plot proprieties.

- AstroModeling crash when estimating parameters.

- AstroModeling linking between plots and points annotations is broken.

- Consider updating BBarolo from 1.4 to 1.5

- AstroMasking crash when doing a Crop operation on a Region of Interest.

- Replace old wigets with new annotation widgets (e.g.: Ruler with the new line widget in the AstroPVSlice module)

- Fix compilation of wcslib for windows for having SlicerAstro binaries for windows too.

- Consider updating wcslib from 5.18 to 6.4

- Consider updating cfitio from 3.450 to 3.470

## Approach and Plan
Prioritize items in the to do list and implement them.

## Progress and Next Steps


# Illustrations
[![](https://raw.githubusercontent.com/Punzo/SlicerAstroWikiImages/master/Screenshot-SlicerAstro-ProjectWeek2020.png)](http://www.youtube.com/watch?v=D-4G9lKVjaY "Wein069")

# Background and References
SlicerAstro extends 3DSlicer to provide a 2D/3D interactive viewer for astronomical datasets with 3D interaction features,
based on traditional 2D input/output hardware, and visual analytics capabilities.


For more informations refer to this [link](https://github.com/Punzo/SlicerAstro/wiki#slicerastro-publications).


[punzo]: https://github.com/Punzo
[punzodavide]: https://www.davidepunzo.com/
[slicerastroissue]: https://github.com/Punzo/SlicerAstro/issues/106

