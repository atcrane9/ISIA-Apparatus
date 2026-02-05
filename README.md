# ISIA-Apparatus

The "Immersive Social Interactions Assay" (ISIA) apparatus is a modular system designed to connect multiple mouse cages together, while allowing the option to restrict certain mice to specific cages.

The link to methods paper for this apparatus can be found [here] ()

## Hardware

All files were printed using a Prusa i3 MKS3\
Nozzles used were either 0.4mm or 0.6mm, depending on specific part (Instructions for changing the nozzles [here](https://help.prusa3d.com/article/changing-or-replacing-the-nozzle-mk2-5-s-mk3-s-mk3-5-s_2069))
* **<ins>Must</ins>** be printed using **<ins>0.4mm nozzle</ins>**
  * [Cap](STL_Files/ISIA_Cap.stl)
  * [Adapter](STL_Files/ISIA_Adapter.stl)
  * [Inner Gate](STL_Files/ISIA_Inner_Gate.stl)
  * [Outer Gate](STL_Files/ISIA_Outer_Gate.stl)
* Can be printed using **<ins>0.6mm nozzle</ins>**
  * [Tube](STL_Files/ISIA_Tube.stl)
  * [Restrictor](STL_Files/ISIA_Restrictor.stl)

## Software

All parts sliced (aka rendered) using PrusaSlicer 2.9.2

Full print settings found here:\
[0.4mm nozzle settings](PrinterSettings/0.4nozzle_settings_no_support.ini)\
[0.6mm nozzle settings](PrinterSettings/0.6nozzle_settings_no_support.ini)

### Key Settings
* No skirt, no brim, no support material, no raft 
* First layer speed: 10mm/s 
* First layer height: 0.2mm 
* Infill density: 5%
* Layer Height:
  * For **<ins>0.4mm</ins>** Nozzle -> 0.3mm layer height
  * For **<ins>0.6mm</ins>** Nozzle -> 0.4mm layer height
  

# Acknowledgments

* [Aaron Crane](https://github.com/atcrane9) - Original designs for the Cap, Adapter, Inner and Outer Gates, updates to the Tube design, and compatibility of entire ensamble
* [The AER Lab](https://github.com/AER-Lab)
* [Matt Gaidica](https:// github.com/mattgaidica) - First iteration design of Tube, Restrictor (Insert), and Flange
