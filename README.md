<div align="center">

# Skilleton 10" Server Rack Framework

<img src="materials/preview-4-3.png" alt="Shelf mounts" width="500">

</div>
<br>

- [Skilleton on MakerWorld](TODO)
- [Skilleton on Printables](TODO)

**Skilleton** is a fully open-source, 3D-printable framework designed for constructing custom server and network racks
for homelab environments. Built around a modular 1U-factor grid, it allows users to scale, stretch, and compose
enclosures tailored precisely to specific hardware footprints

While optimized natively for 10-inch hardware, Skilleton avoids rigid dimension locks. Its height, width, and depth are
entirely defined by swappable, modular structural segments, making the system fully customizable

🚀 **Key Specifications & Features**

- **1U Grid Modularity:** Highly extensible layout based on standard 1U height intervals
- **Fully Custom Dimensions:** Adaptable width, depth, and height via interchangeable segments to fit non-standard
  hardware
- **Hardware Integration:** Features an integrated captive nut design for robust component mounting and assembly
- **100% 3D Printable:** Optimized for standard desktop 3D printers without requiring specialized manufacturing tools
- **Open Source:** Fully accessible architecture for community modifications and custom segment developments

🏋 **Structural Integrity & Load Ratings**

- **Component Static Load:** Standalone structural PETG segments successfully completed static load testing at **12kg**
  with zero structural failure or permanent deformation
- **Assembled Assembly Capacity:** In active deployment, a fully assembled PETG 8U Skilleton configuration continuously
  supports a **9kg** multi-node homelab setup without structural fatigue

## ⚙️ Print Specifications

A standard 6U Skilleton 10-inch rack configuration requires:

- **Filament:** ~700g of PETG (or technical filaments with equivalent mechanical properties)
- **Time:** ~26 hours
- **Layer Height:** 0.2mm
- **Infill:** 30% Gyroid
- **Wall Loops:**
    - **5 walls** for all handle components
    - **4 walls** for all other structural components

## 🔩 Bill of Materials

Aside from the filament, assembling the **Skilleton** rack requires only standard metric fasteners. All
integrated slots are engineered to fit standard DIN 934 hex nuts, removing the need for proprietary hardware or heat-set
tools

### Material Types

- M4 x 20mm screws
- M4 nuts DIN 934 hex nuts
- M6 x 16mm screws
- M6 nuts DIN 934 hex nuts

### Baseline Quantities [(for a 6U 10-inch configuration)](files/6U-rack-bundle.3mf)

- **M4 x 20mm screws and nuts:** **~60 pieces are required** to connect all structural supports, stands, and connectors
- **M6 x 16mm screws and nuts:** **A minimum of 16 pieces is strictly required** to properly secure the main server rack
  stands, feet and caps. The total additional amount depends entirely on how many rackmount devices, panels, or
  adapters you plan to install

## 📦 Files

- [6U 10-inch server rack bundle Bambu Studio .3mf file](files/6U-rack-bundle.3mf)
- [All available components bundle Bambu Studio .3mf file](files/skilleton.3mf)
- [Autodesk Fusion .f3d file](files/skilleton.f3d)
- [.step file](files/skilleton.step)

## 🧩 Available Components

### Stands

The primary vertical structural elements that dictate the rack's Rack Unit (RU) capacity and provide the main mounting
interface for equipment

- **Standard Rack Compliance:** Engineered to follow standard server rack vertical spacing specifications, serving as
  the native mounting interface for rack-mountable hardware
- **M6 Equipment Sockets:** Features dedicated, integrated captive sockets for standard M6 screws and nuts to securely
  fasten rack units
- **M4 Accessory & Support Sockets:** Equipped with integrated M4 screw and nut sockets. These serve a dual purpose:
  securing the rack's horizontal structural supports and acting as modular extension points for attaching side panels,
  cable management, or custom add-ons
- **Mirrored Geometry:** Due to their asymmetrical structural design, these components are delivered as distinct left-
  and right-handed parts. They must be printed in mirrored pairs to assemble a functional rack layer
- **Modular Grid Configurations:**
    - 1U
    - 2U

#### Preview

<details>
<summary>Printed</summary>

<img src="materials/stands/stands1.jpeg" alt="stands1" width="400">
<img src="materials/stands/stands2.jpeg" alt="stands2" width="400">
<img src="materials/stands/stands3.jpeg" alt="stands3" width="400">
<img src="materials/stands/stands4.jpeg" alt="stands4" width="400">
<img src="materials/stands/stands5.jpeg" alt="stands5" width="400">
<img src="materials/stands/stands6.jpeg" alt="stands6" width="400">
<img src="materials/stands/stands7.jpeg" alt="stands7" width="400">
<img src="materials/stands/stands8.jpeg" alt="stands8" width="400">
<img src="materials/stands/stands9.jpeg" alt="stands9" width="400">
<img src="materials/stands/stands10.jpeg" alt="stands10" width="400">
<img src="materials/stands/stands11.jpeg" alt="stands11" width="400">

</details>

<details>
<summary>3D</summary>

<img src="materials/stands/3d-stands1.png" alt="3d-stands1" width="400">
<img src="materials/stands/3d-stands2.png" alt="3d-stands2" width="400">
<img src="materials/stands/3d-stands3.png" alt="3d-stands3" width="400">

</details>

### Supports

The structural cross-members that bridge the vertical stands to establish the rack's footprint and ensure overall
framework rigidity

- **Dimensional Definition:** Acts as the primary components that dictate both the total width and total depth of the
  server rack configuration
- **Horizontal Stability:** Provides critical lateral bracing to eliminate structural sway and maintain square alignment
  under load
- **Modular Grid Configurations:** Available in multiple width x height sizing options to allow for custom modular
  scaling:
    - 2x2U
    - 2x1U
    - 1x2U
- **Integrated Cable Management:** Features molded pass-through 3mm holes optimized for zip ties or hook-and-loop
  fasteners to facilitate clean internal cable routing

#### Preview

<details>
<summary>Printed</summary>

<img src="materials/supports/supports1.jpeg" alt="supports1" width="400">
<img src="materials/supports/supports2.jpeg" alt="supports2" width="400">
<img src="materials/supports/supports3.jpeg" alt="supports3" width="400">
<img src="materials/supports/supports4.jpeg" alt="supports4" width="400">

</details>

<details>
<summary>3D</summary>

<img src="materials/supports/3d-supports1.png" alt="3d-supports1" width="400">
<img src="materials/supports/3d-supports2.png" alt="3d-supports2" width="400">
<img src="materials/supports/3d-supports3.png" alt="3d-supports3" width="400">

</details>

### Handles

Dual-purpose components that integrate directly into the framework's horizontal layout, serving simultaneously as
structural cross-members and lifting points

- **Structural Integration:** Designed to merge seamlessly into the support composition, functioning actively as a
  load-bearing element that maintains overall frame rigidity
- **Dual-Function Design:** Eliminates the need for dedicated, non-structural add-ons by acting as both a standard
  framework support and a robust transport grip
- **Modular Grid Configurations:** Available in multiple scaling options (width x height) to match your custom support
  layout:
    - 2x2U
    - 2x1U
    - 4x2U
    - 4x1U

#### Preview

<details>
<summary>Printed</summary>

<img src="materials/handles/handles1.jpeg" alt="handles1" width="400">
<img src="materials/handles/handles2.jpeg" alt="handles2" width="400">
<img src="materials/handles/handles3.jpeg" alt="handles3" width="400">

</details>

<details>
<summary>3D</summary>

<img src="materials/handles/3d-handles1.png" alt="3d-handles1" width="400">
<img src="materials/handles/3d-handles2.png" alt="3d-handles2" width="400">
<img src="materials/handles/3d-handles3.png" alt="3d-handles3" width="400">

</details>

### Adapters & Spacers

Auxiliary structural components designed to accommodate specific hardware configurations and geometric transitions
within the framework

**Back Support Adapters**

- **Purpose:** Enables horizontal support segments to function as a rear back-plate
- **Orientation & Marking:** Produced as mirrored components with integrated orientation markings relative to the stand
  position: TL (Top Left), TR (Top Right), BL (Bottom Left), and BR (Bottom Right)
- **Assembly Tolerance:** The geometric variations between these four adapters are minimal. Due to the intrinsic
  flexibility of the 3D-printed stands, these orientation markings can be safely ignored during assembly, as the
  material easily compensates for the minor structural differences

**Spacers**

- **Purpose:** Fastener length compensation inserts used when securing the vertical stands
- **Hardware Compatibility:** Required specifically when assembling the framework with M4 x 20mm screws and nuts
- **Optional Substitution:** These components are entirely optional; users can eliminate the need for spacers by
  substituting the hardware with shorter M4 x 10mm screws

#### Preview

<details>
<summary>Printed</summary>

<img src="materials/adapters/adapters1.jpeg" alt="adapters1" width="400">
<img src="materials/adapters/adapters2.jpeg" alt="adapters2" width="400">
<img src="materials/adapters/adapters3.jpeg" alt="adapters3" width="400">

</details>

<details>
<summary>3D</summary>

<img src="materials/adapters/3d-adapters1.png" alt="3d-adapters1" width="400">
<img src="materials/adapters/3d-adapters2.png" alt="3d-adapters2" width="400">

</details>

### Stand Feet

Base components designed to provide a secure and stable foundation for the assembled framework. Functions as the direct
contact interface with the desk or floor, protecting supporting surfaces from scratches

#### Preview

<details>
<summary>Printed</summary>

<img src="materials/feet/feet1.jpeg" alt="feet1" width="400">
<img src="materials/feet/feet2.jpeg" alt="feet2" width="400">

</details>

<details>
<summary>3D</summary>

<img src="materials/feet/3d-feet1.png" alt="3d-feet1" width="400">
<img src="materials/feet/3d-feet2.png" alt="3d-feet2" width="400">

</details>

### Stand Caps

Termination components designed to cap the upper edges of the vertical stands while maintaining hardware mounting
functionality

- **Top-Edge Mounting Interface:** Provides integrated sockets for M6 and M4 screws and nuts at the very top of the
  framework

#### Preview

<details>
<summary>Printed</summary>

<img src="materials/caps/caps1.jpeg" alt="caps1" width="400">
<img src="materials/caps/caps2.jpeg" alt="caps2" width="400">

</details>

<details>
<summary>3D</summary>

<img src="materials/caps/3d-caps1.png" alt="3d-caps1" width="400">
<img src="materials/caps/3d-caps2.png" alt="3d-caps2" width="400">
<img src="materials/caps/3d-caps3.png" alt="3d-caps3" width="400">

</details>

