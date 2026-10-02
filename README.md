# Project M.E.T.S.

## Multi-Electron Transport Solid-State Battery Architecture

[![MIT Solve 2027](https://img.shields.io/badge/MIT%20Solve-2027%20Climate%20Challenge-orange.svg)](https://solve.mit.edu)
[![Form Factor](https://img.shields.io/badge/Form%20Factor-CR2032%20%7C%20Pouch%20Compatible-blue.svg)](#key-specifications)
[![Safety Profile](https://img.shields.io/badge/Safety-Non--Flammable%20(SET%20=%200s)-emerald.svg)](#core-innovations)
[![Architecture](https://img.shields.io/badge/Architecture-In--Situ%20Quasi--Solid--State-purple.svg)](#how-it-works)

A drop-in quasi-solid-state lithium metal battery architecture engineered to eliminate thermal runaway hazards while remaining 100% compatible with existing high-speed battery manufacturing infrastructure.

---

## ⚡ Interactive 3D Cell Anatomy

This repository includes a standalone, photorealistic 3D WebGL model (`index.html`) demonstrating the internal layer-by-layer anatomy of the M.E.T.S. cell architecture.

- **Exploded & Sealed Views:** Interactive continuous slider animating the transition between hermetically crimped and exploded mechanical states.
- **Micro-Interfacial Inspection:** Visualizes the conformal contact between the in-situ crosslinked gel-polymer matrix, cathode active particles, and the lithium metal anode.
- **Dynamic Leader Lines & HUD:** Real-time dynamic SVG callouts detailing layer thicknesses, material selections, and mechanical stack physics.
- **Dual Visual Themes:** High-contrast Titanium Dark and Studio Light modes.

> **To View Locally:** Clone the repository and double-click `index.html` in any modern web browser (no local server or build tools required).

---

## 🎯 The Core Problem

Conventional lithium-ion batteries rely on volatile liquid organic electrolytes that present severe thermal runaway risks, causing battery fires in electric vehicles and consumer devices. Globally, rapid battery obsolescence generates over 100,000 tons of hazardous electronic waste annually, releasing toxic heavy metals into vulnerable communities.

To address safety and energy density, industry leaders are pursuing all-solid-state batteries. However, ceramic and sulfide solid electrolytes are extremely brittle and require continuous multi-megapascal stack pressures to function without interfacial failure. Retooling gigafactories for all-solid-state manufacturing has caused manufacturers between $500M and $1.8B in yield losses and commercialization delays.

---

## 💡 The M.E.T.S. Solution

Project M.E.T.S. resolves this industrial impasse through a **quasi-solid-state drop-in architecture**:

1. **In-Situ Thermal Polymerization with LiTFSI Salt:** The cell is injected with a low-viscosity liquid precursor containing crosslinkable acrylate monomers, flame-retardant organophosphates, and dissolved Lithium Bis(trifluoromethanesulfonyl)imide (LiTFSI) conductive salt. The bulky TFSI anion facilitates high salt dissociation and rapid lithium-ion mobility without the hydrofluoric acid degradation risks of traditional salts. Upon mild thermal activation post-sealing (60°C), the precursor cures directly within the cell to form a robust 3D gel-polymer network.
2. **Conformal Interfacial Contact:** Because polymerization occurs *after* liquid infiltration, the polymer wets 100% of the active cathode pores, eliminating the massive interfacial impedance typical of dry ceramic solid electrolytes.
3. **Intrinsic Fire Suppression:** Integrated non-flammable organophosphate chemistry captures combustion free radicals during electrical or thermal stress, achieving a Self-Extinguishing Time (SET) of 0 seconds.
4. **Mechanical Dendrite Suppression:** The dense crosslinked matrix and high stack uniformity prevent localized current hotspots, suppressing sharp lithium dendrite nucleation.
5. **Zero Factory Retooling:** Operates seamlessly on existing roll-to-roll assembly lines without requiring multi-billion-dollar factory redesigns.

---

## 📊 Key Specifications (CR2032 Baseline Prototype)

| Parameter | Specification | Design Rationale |
| :--- | :--- | :--- |
| **Form Factor** | CR2032 (Ø 20.0 x 3.2 mm) | Standardized IEC 60086-3 coin cell baseline |
| **Casing Material** | Stainless Steel SS316L | High corrosion resistance across broad electrochemical window |
| **Electrolyte System** | In-situ crosslinked gel-polymer | Eliminates free liquid solvent leakage and thermal runaway |
| **Fire Safety Rating** | Self-Extinguishing Time (SET) = 0s | Chemically arrests thermal runaway upon puncture or overcharge |
| **Anode System** | Lithium Metal Disc / Composite Host | High gravimetric energy density |
| **Internal Spacer** | 1.0 mm Ground SS316L Planar Disc | Guarantees uniform mechanical stack pressure without point fatigue |
| **Manufacturing Fit** | Standard Roll-to-Roll & Vacuum Injection | 100% drop-in compatibility with existing lithium-ion factory lines |

---

## 🔒 Intellectual Property & Trade Secret Notice

This public repository contains architectural overviews, mechanical cell stack models, and non-confidential performance criteria designed to demonstrate technical proof of concept for the **MIT Solve 2027 Global Climate Challenge**.

> **Notice:** Specific chemical precursor monomer ratios, proprietary initiator molarities, thermal polymerization curing schedules, and detailed laboratory standard operating procedures (SOPs) are strictly retained as confidential trade secrets and proprietary intellectual property.

---

## 👤 Project Leadership

* **Lead Innovator:** Neeraj Bhupendra Patekar
* **Project:** M.E.T.S. (Multi-Electron Transport Solid-State)
* **Application:** MIT Solve 2027 Global Climate Challenge
