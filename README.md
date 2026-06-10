# RFTP2917
## Description
- RF Test Pad for 2917 Package, designed in Altium Designer.
- Board dimension: 60mm x 25mm
- RF trace: impedance control at 50Ω, ~0.5mm width
## Design Updates
### V1.0
- Initial board design
![3d Model](TP3D2917_v1.png)
### V1.1
- The RF input pin geometry is wider than the required 50 Ω microstrip width so gradual tapered transition was introduced from the pin pad to the 50 Ω RF trace. The taper helps provide a smoother impedance transition and reduces potential return loss at the interface.
- A ground-pour extension was added near the RF input component to utilize the available clearance area and maintain ground proximity to the RF trace as much as possible.
![3d Model](TP3D2917.png)
