# Capillary Pressure Curve Tool

An interactive Python desktop application for generating capillary pressure curves using the **Brooks-Corey model**. Users can input parameters like irreducible water saturation (Swi), entry pressure (Pce), pore size distribution index (lambda), and water saturation (Sw) range to visualize how capillary pressure varies with saturation.

---

## Features

- Supports both **sandstone** and **shale** rock types
- Accepts user-defined:
  - Swi (irreducible water saturation)
  - Pce (entry pressure in psi)
  - Lambda (pore size distribution index)
  - Sw range (start and end saturation)
- Uses the **Brooks-Corey equation** for capillary pressure
- Visual output of Pc–Sw curve
- Desktop interface (Tkinter-based or Streamlit version)

---

## Installation

Clone the repository:

```bash
git clone https://github.com/potabir/capillary-pressure.git
cd capillary-pressure
