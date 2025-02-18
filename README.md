# Weather_Link_PDB_v1.0
**PCB**
<p align="center">
<img src="https://gitlab.com/Akshay_chandran/weatherlink_pdb/-/raw/master/Images/Weatherlink_img4.jpg" width="600"/>

</p>


**3D IMAGE**
<p align="center">
<img src="https://gitlab.com/Akshay_chandran/weatherlink_pdb/-/raw/master/Images/Weather_Link_4.jpg" width="300"/>
<img src="https://gitlab.com/Akshay_chandran/weatherlink_pdb/-/raw/master/Images/Weather_Link_5.jpg" width="300"/>
</p>



## Project Description

Weather_Link_PDB_v1.0 is a PCB designed as a HAT for the [C1_dev_v1.0](https://gitlab.com/icfoss/OpenIoT/c1_dev_v1.0), which can be inserted into the Weather_Link system. It can be used for both AWS (Automatic Weather Station) and RLS (Radar Level Sensor) projects. The design includes the necessary components and layout to ensure efficient performance and seamless integration with the Weather_Link platform.

---

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Requirements](#requirement)
- [Design](#design)
  - [Step 1: Creating the Schematic](#step-1-creating-the-schematic)
  - [Step 2: Assigning Footprints](#step-2-assigning-footprints)
  - [Step 3: PCB Layout](#step-3-pcb-layout)
  - [Step 4: Generating Gerber Files](#step-4-generating-gerber-files)
- [Contributors](#contributors) 
- [License](#license)
- [Contact Information](#contact-information)


---
## Features

- Designed in KiCad 8.0
- Supports multiple sensors
- IoT connectivity for remote monitoring
- Optimized PCB layout for efficient performance

---

## Requirement

- KiCad 8.0


---

## Design


### Step 1: Creating the Schematic
Start by designing the schematic in KiCad 8.0 . This step involves:
1. Adding components such as Capacitor, Resistor, Terminal Block, DC to DC Converter, Switch,ect....
2. Defining connections between components.

**PCB Schematic:** 

<img src="https://gitlab.com/Akshay_chandran/weatherlink_pdb/-/raw/master/Design%20File/Schematics/Weather_Link_PDB_V1.0.png" width="600"/>
</p>

<!-- [Weather_Link_PDB_v1.0 Schematic](https://gitlab.com/Akshay_chandran/weatherlink_pdb/-/blob/master/Design%20File/Schematics/Schematics.pdf?ref_type=heads) -->



### Step 2: Assigning Footprints
After completing the schematic, assign footprints to each component:
1. Use the "Assign Footprints" tool in KiCad.
2. Ensure all footprints are compatible with your PCB layout.

**Footprints:** 

<img src="https://gitlab.com/Akshay_chandran/weatherlink_pdb/-/raw/master/Images/Footprint.png" width="600"/>
</p>



### Step 3: PCB Layout
Proceed to the PCB layout design in KiCad's Pcbnew:
1. Import the schematic netlist.
2. Arrange components on the PCB.
3. Route the connections, ensuring proper signal flow.
4. Verify design rules and clearance.

**PCB Layout :**

<img src="https://gitlab.com/Akshay_chandran/weatherlink_pdb/-/raw/master/Images/Weather_Link_1.png?ref_type=heads" width="600"/>
</p>

<!-- [Weather_Link_PDB_v1.0 Layout](https://gitlab.com/Akshay_chandran/weatherlink_pdb/-/raw/master/Images/Weather_Link_1.png?ref_type=heads) -->



### Step 4: Generating Gerber Files
Once the PCB layout is complete, generate Gerber files for manufacturing:
1. Use the "Plot" tool to create Gerber files.
2. Ensure you include drill files and board outline.

**Gerber Files:** 

<p align="center">
<img src="https://gitlab.com/Akshay_chandran/weatherlink_pdb/-/raw/master/Images/Drill_file.png" width="300"/>
<img src="https://gitlab.com/Akshay_chandran/weatherlink_pdb/-/raw/master/Images/F_CU_File.png" width="300"/>
</p>


### Contributors

<div style="display: flex; justify-content: center; align-items: center; gap: 20px;">
  <div style="text-align: center;">
    <a href="https://gitlab.com/jaison_j" style="text-decoration: none; color: inherit;">
      <img src="https://gitlab.com/uploads/-/system/user/avatar/3760735/avatar.png?width=800" width="100" style="border-radius: 50%;" alt="Jaison Jacob" />
      <br />
      <span style="font-size: 14px;">Jaison Jacob</span>
    </a>
  </div>
  
  <div style="text-align: center;">
    <a href="https://gitlab.com/Akshay_chandran" style="text-decoration: none; color: inherit;">
      <img src="https://gitlab.com/uploads/-/system/user/avatar/25453230/avatar.png?width=800" width="100" style="border-radius: 50%;" alt="Akshay Chandran" />
      <br />
      <span style="font-size: 14px;">Akshay Chandran</span>
    </a>
  </div>
  <div style="display: flex; justify-content: center; align-items: center; gap: 20px;">
  <div style="text-align: center;">
    <a href="https://gitlab.com/abdularshadvs" style="text-decoration: none; color: inherit;">
      <img src="https://gitlab.com/uploads/-/system/user/avatar/12315067/avatar.png?width=800" width="100" style="border-radius: 50%;" alt="Abdul Arshad" />
      <br />
      <span style="font-size: 14px;">Abdul Arshad</span>
    </a>
  </div>
  <div style="text-align: center;">
    <a href="https://github.com/aiswaryaaishh" style="text-decoration: none; color: inherit;">
      <img src="https://avatars.githubusercontent.com/u/157362927?v=4" width="100" style="border-radius: 50%;" alt="Aiswarya Babu" />
      <br />
      <span style="font-size: 14px;">Aiswarya Babu</span>
    </a>
  </div>
</div>

## License
This project is licensed under the MIT License - see the [LICENSE](https://gitlab.com/Akshay_chandran/weatherlink_pdb/-/blob/master/LICENSE?ref_type=heads) file for details.

## Contact Information

You can find us at:

**ICFOSS**<br>
Greenfield Stadium,<br>
Opposite University of Kerala Campus, Karyavattom,<br>
Thiruvananthapuram, Kerala 695581

For more information, visit our [website](https://icfoss.in/).

--------------------------------------
