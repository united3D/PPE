# Face Shield

Our face shield design is based on the Prusa design. To learn more about it, visit [their site](https://www.prusaprinters.org/prints/27950-prusa-face-shield-us-version).

**Under development. Please refrain from printing unless you receive permission from your regional managers.**

As of **5/27/20**, please use `headband_v12.stl` as the primary headband design.

## PROCESS
In order to create a face shield, there are a couple of prints required. Please print the following:

* `headband_v{latest version}.stl`
* `bottom_reinforcement.stl`
* `Clips.gcode - please email divi@united3d.org if download does not work`


In order to make the actual shield, you will need to cut polycarbonate. Please ask your regional manager for instructions regarding the polycarbonate.

## Settings
Here are some settings that we recommend (depending on your printer):

* Quality:
	*    (PowerSpec) Layer Height - 0.2~0.22 
	*    (Prusa) Layer Heigth - 0.3
	*    (LulzBot) Layer Height - 0.3
	*    Initial Layer - 0.15
	*    Line Width (headband) - 0.5
	*    Line Width (bottom reinforcement(BR)) - 0.3
* Shell:
	*    Wall Thickness - 1
	*    Wall count - 1
	*    Top/Bottom Thickness - 0.6
	*    Top/Bottom Layers - 3
	*    Alternate Walls - yes
* Infill:
	*    Infill Density (headband) - 75%
	*    Infill Density (bottom reinforcement) - 50%
	*    Infill Pattern - (can be used) Grid / (recommended) Triangle
* Material:
	*    PLA (use manufacturer's instructions)
* Speed:
	*    Print Speed - 60
* Cooling:
	*    Enable Print Cooling
	*    Fan Speed - 100%
* Support:
	*    Disable Support
* Build Plate Adhesion:
	*	Initial Layer Build Plate: 70˚ C
	* 	Build Plate: 60˚ C
	*  Disable Plate Adhesion (depends on the printer, if you want to enable it)
		* Lulzbot Taz 6: Raft
		* PowerSpec(Wanhao) Duplicator i3: None
		* Original Prusa i3 MK3S: Brim (1 layer)

---
The above has been tested on the follwing printers:

* PowerSpec(Wanhao) Duplicator i3 
* Lulzbot Taz 6
* Original Prusa i3 MK3S

If the above works for your printer, and is not mentioned here, please notify your regional manager.

## License
The designs are based off of Prusa3D designs. Visit [Prusa3D](https://www.prusa3d.com/) to learn more about the designs. 
