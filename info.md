# 📅 ESP32 Modular Portable Dev Board – Side Hustle Plan

**Goal:**  
Design, build, and document a portable ESP32 development board with:
- Built-in mini breadboard
- Li-ion battery power
- Storage space for jumper wires and sensors
- Modular GPIO breakout for quick testing

---

## 🛠 Tools & Platforms
- **PCB Design**: EasyEDA  
- **Firmware**: ESP-IDF (FreeRTOS)  
- **Mechanical Design**: Fusion 360 or FreeCAD  
- **Task Tracking**: Trello / Notion  
- **Code & Files Hosting**: GitHub  
- **References Storage**: Google Drive / Notion  

---

## 📦 Weekly Commitment
**3 hours/week** split as:
- 1 hr learning/research
- 2 hrs application/design/build

---

## 📌 Project Phases

### **Phase 1 – Foundation & Planning** (Weeks 1–3)
**Tasks**
- Define feature list and block diagram
- Research ESP32 reference schematics
- Study breadboard integration with PCB
- Sketch enclosure concept
- Organize datasheets and references

**References**
- [EasyEDA Docs](https://docs.easyeda.com/)
- [ESP32 Hardware Design Guidelines](https://www.espressif.com/sites/default/files/documentation/esp32_hardware_design_guidelines_en.pdf)

**Deliverable**:  
Block diagram + feature list + enclosure sketch

---

### **Phase 2 – PCB Design** (Weeks 4–6)
**Tasks**
- Draw schematic in EasyEDA
- Add USB-UART bridge, Li-ion charging circuit
- Place components & route PCB
- Run ERC/DRC checks
- Export Gerber & order PCB

**References**
- [EEVblog PCB Playlist](https://www.youtube.com/playlist?list=PLvOlSehNtuHsqae6F2J4P0i9sZl3o6eNU)
- EasyEDA routing tips (YouTube)

**Deliverable**:  
PCB schematic + layout + Gerber files

---

### **Phase 3 – Assembly & Basic Firmware** (Weeks 7–9)
**Tasks**
- Solder PCB & assemble components
- Test power & USB programming
- Write basic GPIO/I²C/SPI/UART test code
- Verify breadboard connectivity

**References**
- [ESP-IDF Programming Guide](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/)
- [Random Nerd Tutorials – ESP32](https://randomnerdtutorials.com/projects-esp32/)

**Deliverable**:  
Assembled working PCB + basic firmware

---

### **Phase 4 – FreeRTOS Integration & Enclosure** (Weeks 10–12)
**Tasks**
- Implement FreeRTOS tasks (LED, sensor read, serial output)
- Monitor battery voltage in firmware
- Design enclosure in Fusion 360
- Fit PCB, breadboard, and storage compartments

**References**
- [FreeRTOS Documentation](https://www.freertos.org/)
- Fusion 360 Basics (YouTube: “Fusion 360 for Makers”)

**Deliverable**:  
Running FreeRTOS firmware + functional enclosure

---

### **Phase 5 – Polish & Portfolio** (Weeks 13–15)
**Tasks**
- Test portability & usability
- Take high-quality photos & short demo video
- Write GitHub README with:
  - Project summary
  - BOM (Bill of Materials)
  - Schematics & PCB files
  - 3D enclosure files
  - Firmware code

**References**
- GitHub README best practices (Markdown Guide)
- [Example Hardware Project Repo](https://github.com/)

**Deliverable**:  
Complete GitHub repo + portfolio-ready documentation

---

## 🗂 Task Tracking Setup
1. **Trello Columns**:
   - To Do
   - Doing
   - Done
2. **Labels**:
   - Hardware
   - Firmware
   - Enclosure
   - Documentation
3. **Card Contents**:
   - Short task title
   - Checklist
   - Links to datasheets/tutorials
   - Attachments (images, PDFs)

---

## ✅ Success Criteria
- Portable ESP32 board fully working
- Breadboard & modular sensor interface tested
- Enclosure stores battery & jumper wires neatly
- GitHub repo with professional documentation
- Ready to showcase in resume & internship interviews

