---
layout: project
title: Blade Design 
description: Advanced CAD Project
technologies: [Autodesk Fusion 360, MATLAB, Wind Tunnel]
image: assets/images/newcad.png
---

## Project Overview
This project involved the design, fabrication, and experimental testing of small-scale wind turbine blades in a controlled wind tunnel. Resin 3D-printed blades were mounted to a standardized hub and tested using a magnetic particle brake to apply controlled torque and directly measure power output. The primary goal was to maximize power, with constraints on geometry, rotational speed, torque, and structural strength governed by Accura 25 resin and a minimum safety factor of three. A physics-based design approach was used to select a NACA 4412 airfoil and determine blade pitch, twist, and chord taper to maintain favorable angles of attack while limiting root bending stresses. Two blade iterations were tested, with the first underperforming due to twist and angle errors that informed a refined second design. The final iteration satisfied all constraints and demonstrated the importance of iterative testing in reconciling aerodynamic theory with practical small-scale turbine performance.

## Design Process
Our blade design investigated whether a thin, lightweight turbine blade could produce consistent power while maintaining structural integrity at high RPM under given project constraints. We selected a 5.75-inch blade length to maximize scale and used the NACA 4412 airfoil due to its strong lift characteristics and forgiving behavior at the low Reynolds numbers typical of small wind tunnels. This airfoil directly influenced our lift, drag, torque, and root bending moment calculations, making it critical to both aerodynamic performance and structural loading. Blade pitch, twist, and angle of attack were determined by accounting for changing relative flow direction with radius to avoid stall near the root and overloading near the tip. Chord length was tapered from root to tip to compensate for increasing rotational velocity and to balance lift generation with structural limits of the printed resin material. Finally, we verified that the resulting design operated within a reasonable tip speed ratio, ensuring efficient torque production without excessive drag or structural risk.

## Testing Summary 
To evaluate the actual performance of our wind turbine blade design, we conducted a series of controlled experiments in the MAE 4272 wind tunnel using the standard turbine test setup. The blades were mounted to the provided hub assembly and connected to a magnetic particle torque brake, allowing us to vary mechanical loading while measuring the resulting rotational speed and power output. Wind speed was measured upstream using a pitot-static tube, and all signals were recorded using LabVIEW for later analysis. Testing was performed by holding the wind tunnel at fixed speeds and incrementally increasing the torque brake to generate power vs RPM curves at each wind condition. For each steady operating point, wind velocity, rotational speed, applied torque, and electrical power output were recorded. This process was repeated across multiple tunnel frequencies corresponding to approximate wind speeds of 4.2 m/s, 5.83 m/s, 7.18 m/s, 8.5 m/s, 11.1 m/s, and 13.7 m/s. 

These tests captured the turbine’s behavior over a wide range of operating regimes, including low-power and near-stall conditions.  The collected data were compiled into power vs RPM plots for each wind speed, with all trials retained, including those that produced minimal power or exhibited early stall behavior. From the measured power values, the power coefficient was calculated with air density taken as approximately 1.225 kg/m³. These calculations allowed us to compare experimental performance against theoretical expectations. Including data from underperforming and failed operating conditions was essential for identifying aerodynamic inefficiencies and diagnosing shortcomings in the blade geometry and orientation.

## My Contribution
Aenean tincidunt aliquam arcu, in euismod dui dapibus eu. In placerat, mi et ultrices consequat, quam ligula cursus mauris, in semper neque nibh at est. Maecenas hendrerit dignissim porta. Phasellus nec fringilla dolor. Etiam efficitur nisi sit amet velit pharetra feugiat. Etiam ultrices turpis at leo semper, eleifend scelerisque neque malesuada. Aliquam molestie congue rhoncus. Donec blandit neque dolor, nec tristique mi pretium ac. Mauris tincidunt ullamcorper magna, nec pellentesque mi sagittis quis.


## Figures
- Iteration 1 of Blade Design Power Curves
<img src="/fa25-portfolio-las485/assets/images/PowervsRPM.png"
       style="max-width: 350px; height: auto;">

- Improved Iteration of Blade Design : CAD Model
<img src="/fa25-portfolio-las485/assets/images/NewIterationofBladedesign.png"
       style="max-width: 350px; height: auto;">

- Improved Iteration of Blade Design: Theoretical Power Curves
<img src="/fa25-portfolio-las485/assets/images/Theoreticalpower.png"
       style="max-width: 350px; height: auto;">