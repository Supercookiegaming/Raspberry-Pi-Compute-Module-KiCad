# Raspberry Pi Compute Module Library for KiCad
![Development Status](https://img.shields.io/badge/status-Partial%20Completion-yellow)
## Overview
This repository is designed to provide KiCad users the tools needed to create Raspberry Pi Compute Module carrier boards and compatible compute modules. This library includes symbols, footprints, 3D models and templates* for RPi compute modules. Please follow instructions below to ensure internal library refrences are setup correctly.

This library is designed for use in KiCad 9 versions only. 

###### *not implemented yet
## Install Instructions

###Clone Repository
1. First clone the repository to your desired location using your preferred method. For example 

   `cd desired-repository-location`
   
   `git clone https://github.com/Supercookiegaming/Raspberry-Pi-Compute-Module-KiCad.git`
   
2. Install the symbol librarys by opening KiCad 9 then going to Prefrences>Manage Symbol Librarys...
3. Click the plus symbol in the Symbol Library window. The number of rows added must be equal to the number of libraries you are adding. ie. for both CM4 and CM5 libraries add 2 rows.
4. Set the Nickname of the new row(s) to

   For CM4:
   
   `Raspberry-Pi-CM4`
   
   For CM5:
   
   `Raspberry-Pi-CM5`

6. Set the Library Path to 

   For CM4:
   
   `respository-location/Raspberry-Pi-Compute-Module-KiCad/CM4/CM4 Library/Raspberry-Pi-CM4.kicad_sym`

   For CM5:
   
   `respository-location/Raspberry-Pi-Compute-Module-KiCad/CM5/CM5 Library/Raspberry-Pi-CM5.kicad_sym`
   
8. Click Ok to save.
9. Install the footprint librarys by going to Prefrences>Manage Footprint Librarys...
10. Click the plus symbol in the Footprint Library window. The number of rows added must be equal to the number of libraries you are adding. ie. for both CM4 and CM5 libraries add 2 rows.
11. Set the Nickname of the new row(s) to

    For CM4:
   
    `Raspberry-Pi-CM4`
   
    For CM5:
   
    `Raspberry-Pi-CM5`

12. Set the Library Path to 

    For CM4:
   
    `respository-location/Raspberry-Pi-Compute-Module-KiCad/CM4/CM4 Library/Raspberry-Pi-CM4.pretty`

    For CM5:
   
    `respository-location/Raspberry-Pi-Compute-Module-KiCad/CM5/CM5 Library/Raspberry-Pi-CM5.pretty`
   
13. Click Ok to save.   
14. Add the library's internal path by going to Prefrences > Configure Paths...
15. Click the plus symbol in the Confiure Paths window.
16. Set the Name to

    `KICAD9_USER_RPICM_REPO_DIR`

17. Set the Path to root folder of the repository
    
     `repository-location/Raspberry-Pi-Compute-Module-KiCad`

18. Click Ok to Save
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
