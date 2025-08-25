# Muriel Schematics (Prototype)

> This is an early-stage **prototype** intended as a **wireframe and UI/UX concept** for the future full-featured Muriel Schematics web application.  
> It focuses on layout, interaction flow, and visual design — **not** on complete functionality or production-ready performance.

Muriel Schematics is a browser-based electrical schematic design tool tailored for **South African SANS standards**.  
It enables engineers, electricians, and students to create, edit, and visualize electrical diagrams directly in the browser.

## 🚀 Prototype Features

- **SANS Symbol Library**  
  Includes locally recognized symbols for:
  - Passive Components (Resistor, Capacitor, Inductor, Transformer, Switch, Fuse)
  - Sources (Voltage Source, Current Source, AC Source, Solar Cell, Power Supply)
  - Semiconductors (Diode, Transistor, Op-Amp, LED, Thermistor)
  - Output Devices (Lamp, Motor, Buzzer, Speaker)

- **Interactive Canvas** *(UI only)*  
  - Drag-and-drop symbol placement  
  - Zoom and pan for navigation  
  - Visual connection lines between components

- **Component Properties Panel** *(UI placeholder)*  
  - Editable fields for symbol attributes  
  - Display of connected components and node counts

- **Bill of Materials (BOM)** *(UI placeholder)*  
  - Auto-generated list from placed components  
  - Export-ready format planned for future versions

- **Project Management UI**  
  - Save/load buttons (non-persistent in prototype)  
  - Title block customization fields

## 🛠 Tech Stack

- **Frontend:** Likely React (Vercel deployment)
- **Styling:** SASS/CSS modular design
- **Hosting:** [Vercel](https://vercel.com/)

## 📍 Purpose of This Prototype

This version exists to:
- Test **UI/UX flow** before backend integration
- Validate **symbol library layout** and categorization
- Gather **user feedback** on usability and visual design
- Serve as a **foundation** for the production-ready application

## 📦 Installation (Development)

```bash
# Clone the repository
git clone https://github.com/your-username/muriel-schematics.git

# Navigate into the project folder
cd muriel-schematics

# Install dependencies
npm install

# Start the development server
npm run dev
```

## 📄 License
This project is licensed under the MIT License — see the LICENSE file for details.

## 🤝 Contributing
Since this is a prototype, contributions should focus on:
Improving UI/UX flow
Enhancing symbol library visuals
Suggesting layout refinements

