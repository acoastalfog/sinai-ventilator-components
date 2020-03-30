**NOTE 2020-03-30: *Please as of this moment only produce the one-way check-valve components until further notice. It is likely that our gate valve will change due to regulatory requirements, so adapters must be modified or may become obsolete. The check valve is independent of the gate and has been approved.***

# Mount Sinai Health System Ventilator Model Files
Possible 3D Printed Component Substitutes, Version 6

The Sinai BioDesign Group at the Mount Sinai Health System has developed a set of valves and adapters for printing on ordinary, widely available FDM-style 3D printers, commonly found in makerspaces, institutional prototyping facilities, and home labs. 

Specifically, we are making available two simple-to-print flow adapters, together with a one-way check valve. The check valve is a heavily modified version of an existing open source project, with original project documentation, [build instructions](https://youtu.be/sCIX3egYKQM), and [project files](https://cad.onshape.com/documents/5c996e71d2872726995198bf/w/40c80b6ee82124a954fda09d/e/5520dc2a611624c9350b6dc1) also publicly available. We thank these teams for their effort. Our contributions are for academic study only and we do not endorse their use in any medical application. We are making them available to the community in order to scale out prototyping and research of these components. We are making available our designs together with STEP and Fusion360 files if others choose to take what we have done and modify, and will continually update this page.

## Basic Build Information
* Both sets of parts below should be printed in ordinary PLA with a layer height of 0.2mm. 
* Infill of 20% is more than sufficient for appropriate rigidity. 
* PLA including additives *should not be used*. Other materials can be considered. PETG seems a particularly good option for dimensional accuracy, though this has not yet been tested. ABS should not be used.
* Depending on your cooling capacity you may not require any supports, but your mileage may vary. `adapter_v6_smallMaleMale.stl` and `valve_v6_Female.stl` both include a 90 degree overhang when printed in the correct orientation. Setting the overhang angle to 75 degrees will eliminate unnecessary support structures being generated for threading in each of the valve components.
* Press-fit interfaces between adapters and valves should be lined with teflon tape.

These designs have been fit tested from prints on at least 6 commonly available FDM-style 3D printers, with good intra-printer reliability. For use, prints from the same printer should be paired. The entire set of files has been parameterized around the fit of the male interface to a commonly-available [3/4" brass sweat gate valve](https://www.homedepot.com/p/Everbilt-3-4-in-Brass-Sweat-x-Sweat-Gate-Valve-170-4-34-EB/308593230).

## Inner (Male-Male) and Outer (Female-Female) Flow Adapters
**NOTE 2020-03-30: *Please do not yet produce this part. It is likely that our gate valve will change due to regulatory requirements, so adapters must be modified or may become obsolete.***
* Files are `adapter_v6_largeFemaleFemale.stl` and `adapter_v6_smallMaleMale.stl`.
* Files should be printed in a vertical orientation, but are symmetric along this axis with a normal plane of symmetry, so either orientation is equivalent. 

## Two-Part One-Way Check Valve
* Files are `valve_v6_Female.stl` and `valve_v6_Male.stl`, and can be printed in ordinary PLA.
* Print orientation here *matters*. `valve_v6_Male.stl` must be printed with the threading down toward the build surface, preferably made of glass or other very smooth material. It is important that this interface is as smooth as possible.
* `valve_v6_Female.stl` should be printed with threads up, as this eliminates unnecessary support structures inside the thread cavity, requiring them only for the 90 degree overhang.

Appropriate orientation on the build plate is shown here.

![Check Valve On Glass Build Plate](https://github.com/acoastalfog/sinai-ventilator-components/blob/master/checkValveOnPlate.jpg)

## Check Valve Build Instructions
* Check back later. For now, please see instructions in the parent project [here](https://youtu.be/sCIX3egYKQM).
