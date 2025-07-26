# Raspberry Pi Compute Module Library for KiCad
![Development Status](https://img.shields.io/badge/status-Partial%20Completion-yellow)
## Overview
This repository is designed to provide KiCad users the tools needed to create Raspberry Pi Compute Module carrier boards and compatible compute modules. This library includes symbols, footprints, 3D models and templates* for RPi compute modules. Please follow instructions below to ensure internal library refrences are setup correctly.

This library is designed for use in KiCad 9 versions only. 


## Install Instructions


1. Clone the repository to your desired location using your preferred method. For example 

   `cd desired-repository-location`
   
   `git clone https://github.com/Supercookiegaming/Raspberry-Pi-Compute-Module-KiCad.git`
   
2. Install the symbol librarys by opening KiCad 9 then going to Prefrences>Manage Symbol Librarys...

![Symbol Manager Location](https://github.com/Supercookiegaming/Raspberry-Pi-Compute-Module-KiCad/blob/c2ece7278fceb82b5f2d134c15807eb1f88bc900/Images/Symbol%20Library%20Location.jpg)
   
3. Click the plus symbol in the Symbol Library window. The number of rows added must be equal to the number of libraries you are adding. ie. for both CM4 and CM5 libraries add 2 rows.

![Symbol Plus Button](https://github.com/Supercookiegaming/Raspberry-Pi-Compute-Module-KiCad/blob/c2ece7278fceb82b5f2d134c15807eb1f88bc900/Images/Symbol%20Library%20Plus%20Button.jpg)
   
4. Set the Nickname of the new row(s) to

   For CM4:
   
   `Raspberry-Pi-CM4`
   
   For CM5:
   
   `Raspberry-Pi-CM5`

5. Set the Library Path to 

   For CM4:
   
   `respository-location/Raspberry-Pi-Compute-Module-KiCad/CM4/CM4 Library/Raspberry-Pi-CM4.kicad_sym`

   For CM5:
   
   `respository-location/Raspberry-Pi-Compute-Module-KiCad/CM5/CM5 Library/Raspberry-Pi-CM5.kicad_sym`

   Example of correctly added Symbol Libraries

   ![Correctly added Symbol Libraries](https://github.com/Supercookiegaming/Raspberry-Pi-Compute-Module-KiCad/blob/c2ece7278fceb82b5f2d134c15807eb1f88bc900/Images/Symbol%20Library%20Example.jpg)
   
6. Click Ok to save.
7. Install the footprint librarys by going to Prefrences>Manage Footprint Librarys...

![Footprint Manager Location](https://github.com/Supercookiegaming/Raspberry-Pi-Compute-Module-KiCad/blob/c2ece7278fceb82b5f2d134c15807eb1f88bc900/Images/Footprint%20Library%20Location.jpg)
    
8. Click the plus symbol in the Footprint Library window. The number of rows added must be equal to the number of libraries you are adding. ie. for both CM4 and CM5 libraries add 2 rows.

![Footprint Plus Button](https://github.com/Supercookiegaming/Raspberry-Pi-Compute-Module-KiCad/blob/c2ece7278fceb82b5f2d134c15807eb1f88bc900/Images/Footprint%20Library%20Plus%20Button.jpg)
    
9. Set the Nickname of the new row(s) to

    For CM4:
   
    `Raspberry-Pi-CM4`
   
    For CM5:
   
    `Raspberry-Pi-CM5`

10. Set the Library Path to 

    For CM4:
   
    `respository-location/Raspberry-Pi-Compute-Module-KiCad/CM4/CM4 Library/Raspberry-Pi-CM4.pretty`

    For CM5:
   
    `respository-location/Raspberry-Pi-Compute-Module-KiCad/CM5/CM5 Library/Raspberry-Pi-CM5.pretty`

    Example of correctly added Footprint Libraries:

![Correctly added Footprint Libraries](https://github.com/Supercookiegaming/Raspberry-Pi-Compute-Module-KiCad/blob/c2ece7278fceb82b5f2d134c15807eb1f88bc900/Images/Footprint%20Library%20Example.jpg)
11. Click Ok to save.   
12. Add the library's internal path by going to Prefrences > Configure Paths...

![Configure Path Loction](https://github.com/Supercookiegaming/Raspberry-Pi-Compute-Module-KiCad/blob/c2ece7278fceb82b5f2d134c15807eb1f88bc900/Images/Configure%20Paths%20Location.jpg)
    
13. Click the plus symbol in the Configure Paths window.

![Path Plus Button](https://github.com/Supercookiegaming/Raspberry-Pi-Compute-Module-KiCad/blob/c2ece7278fceb82b5f2d134c15807eb1f88bc900/Images/Configure%20Paths%20Plus%20Button.jpg)
    
14. Set the Name to

    `KICAD9_USER_RPICM_REPO_DIR`

15. Set the Path to root folder of the repository
    
     `repository-location/Raspberry-Pi-Compute-Module-KiCad`
    
Example of correctly added path:

![correctly added path](https://github.com/Supercookiegaming/Raspberry-Pi-Compute-Module-KiCad/blob/c2ece7278fceb82b5f2d134c15807eb1f88bc900/Images/Configure%20Paths%20Exmaple.jpg)

16. Click Ok to Save
## To Do List

| Tasks | Status | Version Milestone |
|-------|--------|--------|
|**CM1 Library**|![Planned](https://img.shields.io/badge/status-planned-blue) |**v0.8**|
|**CM1 Templates**|![Planned](https://img.shields.io/badge/status-planned-blue) |**v0.9**|
|**CM3 & CM3+ Libarary**|![Planned](https://img.shields.io/badge/status-planned-blue) |**v0.6**|
|**CM3 & CM3+ Templates**|![Planned](https://img.shields.io/badge/status-planned-blue) |**v0.7**|
|**CM4 Library**|![Completed](https://img.shields.io/badge/status-completed-brightgreen) |**v0.1**|
|**CM4 Templates**|![Planned](https://img.shields.io/badge/status-planned-blue) |**v0.3**|
|**CM4S Library**|![Planned](https://img.shields.io/badge/status-planned-blue) |**v0.2**|
|**CM4S Templates**|![Planned](https://img.shields.io/badge/status-planned-blue) |**v0.5**|
|**CM5 Library**|![Completed](https://img.shields.io/badge/status-completed-brightgreen) |**v0.1**|
|**CM5 Templates**|![Planned](https://img.shields.io/badge/status-planned-blue) |**v0.4**|


| Bugs | Issue | Status| Version Milestone | Branch |
|-------|--------|--------|--------|--------|
|**Mislabled CM5 MIPI Pins**| [Issue #9](https://github.com/Supercookiegaming/Raspberry-Pi-Compute-Module-KiCad/issues/9) |![Fixed in Branch](https://img.shields.io/badge/status-Fixed_in_Branch-green) | v0.2 | v0.2 |

###### *not implemented yet
