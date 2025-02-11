Made by: [@dave9123](https://dave9123.pages.dev/)

Repository link: [https://github.com/dave9123/GreenSpool](https://github.com/dave9123/GreenSpool)

Time spent so far: 2 hours

## Goals

<li>A plastic hopper and melter to turn plastic waste usable.</li>
<li>Automatic conveyor system for continous printing and part ejection.</li>
<li>Able to print rapidly while maintaining print quality.</li>
<li>An interface to control the queue, settings—heated print bed, extrusion heat, fan speed—, pause printing, changing filaments, and etc.</li>
<li>Supports recording timelapse to view the printing process.</li>
<li>Affordable.</li>

## Day 1 (February 9th 2025)

Today I watched a few YouTube videos on how I can possibly make a 3D printer. Then, I realized about the problem that some of us might be facing—plastic waste (except Singaporeans most likely).

I would like to support multiple plastic types but I started to think, how would the user know what type of plastic are they using?

Data below is taken from [Plastic Material Melt & Mould Temperatures by PlastikCity](https://www.plastikcity.co.uk/useful-stuff/material-melt-mould-temperatures)

| Material                        | Melt Temperature Range (°C) | Mould Temperature Range (°C) | Melt Temperature Range (°F) | Mould Temperature Range (°F) |
| :-----------------------------: | :-------------------------: | :--------------------------: | :-------------------------: | :---------------------------: |
| ABS                             | 190-270                    | 40-80                       | 374-518                    | 104-176                     |
| ABS/PC ALLOY                    | 245-265                    | 40-80                       | 473-509                    | 104-176                     |
| ACETAL                          | 180-210                    | 50-120                      | 356-410                    | 122-248                     |
| ACRYLIC                         | 220-250                    | 50-80                       | 428-482                    | 122-176                     |
| CAB                             | 170-240                    | 40-50                       | 338-464                    | 104-122                     |
| HDPE                            | 210-270                    | 20-60                       | 410-518                    | 68-140                      |
| LDPE                            | 180-240                    | 20-60                       | 356-464                    | 68-140                      |
| NYLON 6                         | 230-290                    | 40-90                       | 446-554                    | 104-194                     |
| NYLON 6 (30% GF)                | 250-290                    | 50-90                       | 482-554                    | 122-194                     |
| NYLON 6/6                       | 270-300                    | 40-90                       | 518-572                    | 104-194                     |
| NYLON 6/6 (33% GF)              | 280-300                    | 40-90                       | 536-572                    | 104-194                     |
| NYLON 11                        | 220-250                    | 40-110                      | 428-482                    | 104-230                     |
| NYLON 12                        | 190-200                    | 40-110                      | 374-392                    | 104-230                     |
| PEEK                            | 350-390                    | 120-160                     | 662-734                    | 248-320                     |
| POLYCARBONATE                   | 280-320                    | 85-120                      | 536-608                    | 185-248                     |
| POLYESTER PBT                   | 240-275                    | 60-90                       | 464-527                    | 140-194                     |
| PET (SEMI CRYSTALLINE)          | 260-280                    | 20-30                       | 500-536                    | 68-86                       |
| PET (AMORPHOUS)                 | 260-280                    | 20-30                       | 500-536                    | 68-86                       |
| POLYPROPYLENE (COPOLYMER)       | 200-280                    | 30-80                       | 392-536                    | 86-176                      |
| POLYPROPYLENE (HOMOPOLYMER)     | 200-280                    | 30-80                       | 392-536                    | 86-176                      |
| POLYPROPYLENE (30% TALC FILLED) | 240-290                    | 30-50                       | 464-554                    | 86-122                      |
| POLYPROPYLENE (30% GF)          | 250-290                    | 40-80                       | 482-554                    | 104-176                     |
| POLYSTYRENE                     | 170-280                    | 30-60                       | 338-536                    | 86-140                      |
| POLYSTYRENE (30% GF)            | 250-290                    | 40-80                       | 482-554                    | 104-176                     |
| PVC P                           | 170-190                    | 20-40                       | 338-374                    | 68-104                      |
| PVC U                           | 160-210                    | 20-60                       | 320-410                    | 68-140                      |
| SAN                             | 200-260                    | 50-85                       | 392-500                    | 122-185                     |
| SAN (30% GF)                    | 250-270                    | 50-70                       | 482-518                    | 122-158                     |
| TPE                             | 260-320                    | 40-70                       | 500-608                    | 104-158                     |

Time spent researching: 2 hours

## Day 2 (February 11th 2025)

I found out that plastics can be harmful when it's heated up. Source:
- https://www.quora.com/I-live-beside-a-PET-plastic-plant-that-was-just-opened-The-smell-in-my-garden-and-home-is-like-an-acrylic-factory-Could-this-be-harmful-to-the-kids-and-myself
- https://www.reddit.com/r/unpopularopinion/comments/vfgs8l/heating_food_or_drinks_in_plastic_and_then/

This might mean that I will need to have an exhaust system along with an air filter (HEPA?) to prevent the user from inhaling the toxic fumes emitted during the printing and moulding.