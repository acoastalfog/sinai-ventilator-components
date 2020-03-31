**NOTE 2020-03-31: *Detailed check valve assembly instructions and a bill of materials have been added to the end of this document.***

**NOTE 2020-03-30: *Please as of this moment only produce the one-way check-valve components until further notice. It is likely that our gate valve will change due to regulatory requirements, so adapters must be modified or may become obsolete. The check valve is independent of the gate and has been approved.***

**NOTE 2020-03-30: *We have included the current version (1.2) of the Mount Sinai Ventilator Splitting Protocol. This protocol is not final, poses significant risks to both patients sharing a single ventilator and does not in any way reflect the normal standard of care within the Mount Sinai Health System. The protocol has not yet been trialed in patients. It is included for academic purposes and for implementation in high-fidelity human patient simulator laboratory settings.***

# Mount Sinai Health System Ventilator Model Files
Possible 3D Printed Component Substitutes, Version 6

The Sinai BioDesign Group at the Mount Sinai Health System has developed a set of valves and adapters for printing on ordinary, widely available FDM-style 3D printers, commonly found in makerspaces, institutional prototyping facilities, and home labs. 

Specifically, we are making available two simple-to-print flow adapters (in folder [adapter](https://github.com/acoastalfog/sinai-ventilator-components/blob/master/adapter)), together with a one-way check valve (in folder [checkValve](https://github.com/acoastalfog/sinai-ventilator-components/blob/master/checkValve)). The check valve is a heavily modified version of an existing open source project, with original project documentation, [build instructions](https://youtu.be/sCIX3egYKQM), and [project files](https://cad.onshape.com/documents/5c996e71d2872726995198bf/w/40c80b6ee82124a954fda09d/e/5520dc2a611624c9350b6dc1) also publicly available. We thank these teams for their effort. Our contributions are for academic study only and we do not endorse their use in any medical application. We are making them available to the community in order to scale out prototyping and research of these components. We are making available our designs together with STEP and Fusion360 files if others choose to take what we have done and modify, and will continually update this page.

## Basic Build Information
* Both sets of parts below should be printed in PLA with a layer height between 0.1 and 0.3mm. We encourage you to print at the largest layer height possible and checking for press-fit and thread compatibility for the adapter and check valve, respectively.
* Print with at least 3 perimeters and at least 3 top and bottom layers.
* Infill of 10-20% is more than sufficient for appropriate rigidity. 
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

![Check Valve On Glass Build Plate](https://github.com/acoastalfog/sinai-ventilator-components/blob/master/media/checkValveOnPlate.jpg)

## Check Valve Build Instructions
### Bill of Materials
* Paired, 3D printed check valves
* Ziploc sandwich bags
* Short (<20mm) M3 screws
* PTFE (Teflon) tape
* Scisors
* Awl, or equivalent
* Allen wrenches (or appropriate  wrench for M3 screw above)

### Instructions

1. Prepare the male valve component for an M3 screw by using an awl or similar cylindrically-shaped tool to slightly widen the central screw socket.

![Male Adapter, Awl, and Short M3 Screw](https://github.com/acoastalfog/sinai-ventilator-components/blob/master/media/Check_1.jpg)

![Widen Outer Male Adapter Socket](https://github.com/acoastalfog/sinai-ventilator-components/blob/master/media/Check_2.jpg)

![Widen Inner Male Adapter Socket](https://github.com/acoastalfog/sinai-ventilator-components/blob/master/media/Check_3.jpg)

2. Using a standard Ziploc or equivalent sandwich bag, cut a single layer of plastic material large enough to entire cover the surface of the male valve component.

![Ziploc Sandwich Bag](https://github.com/acoastalfog/sinai-ventilator-components/blob/master/media/Check_4.jpg)

![Cut Bag Layer](https://github.com/acoastalfog/sinai-ventilator-components/blob/master/media/Check_5.jpg)

3. Using your awl or equivalent device (a  stab incision into the plastic will also work), create a hole in the center of the Ziploc plastic sheet through which the screw will be inserted. Ensure the size of the hole is at a minimum, no wider than the central screw socket on the component itself.

![Create Screw Hole in Sandwich Bag](https://github.com/acoastalfog/sinai-ventilator-components/blob/master/media/Check_6.jpg)

![Resulting Configuration](https://github.com/acoastalfog/sinai-ventilator-components/blob/master/media/Check_7.jpg)

4. Insert the M3 screw, and using considerable downward pressure, screw it in flush and more than finger tight, using an appropriately sized allen (or other, depending on your M3 screw head configuration) wrench. If you find it is difficult to self-start and achieve purchase with the M3 screw, return to step 1 and widen the hole a bit more.

![Screw In M3](https://github.com/acoastalfog/sinai-ventilator-components/blob/master/media/Check_8.jpg)

5. Trim the edges of the Ziploc plastic sheet so that it does not extend beyond the sides of the device.

![Trim Plastic](https://github.com/acoastalfog/sinai-ventilator-components/blob/master/media/Check_9.jpg)

![Completed Baffle/Membrane](https://github.com/acoastalfog/sinai-ventilator-components/blob/master/media/Check_10.jpg)

6. Finally, line the male screw threads in at least 2 layers of PTFE (Teflon) tape, and screw the device together, over hand tight.

![Teflon Lining](https://github.com/acoastalfog/sinai-ventilator-components/blob/master/media/Check_11.jpg)

![Screw Tight](https://github.com/acoastalfog/sinai-ventilator-components/blob/master/media/Check_12.jpg)

![Completed Check Valve](https://github.com/acoastalfog/sinai-ventilator-components/blob/master/media/Check_13.jpg)

Congraulations! You've completed construction of the one-way check valve.
