# Weapons Reforged — Modular Weapon & Proficiency Overhaul (Baldur’s Gate EE / EET)

**Weapons Reforged** is a modular, data‑driven overhaul of weapon usability and proficiency rules for Baldur’s Gate Enhanced Editions and EET. It provides a clean, predictable, and compatibility‑focused framework for universal weapon access, proficiency minimums, class‑restricted proficiency caps, and optional removal of fighting style limits — all without altering item descriptions, weapon stats, or kit definitions.

The mod is designed for long‑term stability, interoperability with large mod stacks, and ease of translation and maintenance.

---

## Repository

GitHub: **https://github.com/CelestialFury-BG/weapons-reforged/**

---

## Project Overview

Weapons Reforged focuses exclusively on:

- Weapon usability flags  
- Proficiency tables  
- Fighting style caps  
- Clean, modular WeiDU patching  

It avoids altering item stats or rewriting kits, ensuring maximum compatibility with other mods. Each component is isolated, optional, and safe to install independently.

The mod is licensed under **CC BY 4.0**, allowing anyone to use, modify, or redistribute it with attribution.

---

## My Role

I am the creator and maintainer of Weapons Reforged, responsible for:

- Designing the modular architecture  
- Writing all WeiDU patching logic  
- Building item‑level and proficiency‑level detection systems  
- Ensuring compatibility with EE, BG2EE, and EET  
- Creating translation‑ready component strings  
- Providing documentation and support for players and modders  

---

## Tools & Technologies

- **WeiDU** — mod installer and patching framework  
- **Infinity Engine Enhanced Editions (BGEE, BG2EE, EET)**  
- **2DA table patching** (clasweap.2da, weapprof.2da, etc.)  
- **Item usability byte patching**  
- **PRETTY_PRINT_2DA** for clean output  
- **Translation system** for multiple languages  

---

## Key Features

### **1. Item‑Level Usability Overhauls**
- Remove all class‑based restrictions from weapons  
- Preserve alignment restrictions  
- Category‑based detection ensures only real weapons are affected  

### **2. Universal Weapon Access**
- All classes can use all weapons (Monks excluded)  
- Patches clasweap.2da safely and predictably  

### **3. Universal Proficiency Minimums**
(Only one may be installed)

- Minimum 1 Pip (Proficient)  
- Minimum 2 Pips (Specialized)  
- Minimum 3 Pips (Mastery)  
- Minimum 4 Pips (High Mastery)  
- Minimum 5 Pips (Grand Mastery)  

Automatically:

- Detects MONK and KENSAI columns  
- Preserves class‑restricted zeros  
- Zeroes obsolete proficiency rows  

### **4. Enhanced Weapon Options**
(Respects class restrictions; only one may be installed)

- Maximum 2 Pips  
- Maximum 3 Pips  
- Maximum 4 Pips  
- Maximum 5 Pips  

### **5. Fighting Style Cap Removal**
Removes default style caps (2/2/2/3) for all classes except Monks and Kensai.

---

## Technical Challenges & Solutions

### **1. Clean, Modular WeiDU Architecture**
**Challenge:** Avoid conflicts with other mods while patching core 2DA tables.  
**Solution:**  
- Component isolation  
- REQUIRE_PREDICATE checks  
- SUBCOMPONENT grouping  
- BUT_ONLY_IF_IT_CHANGES for safe patching  

### **2. Auto‑Detection of Engine Structures**
**Challenge:** Different EE/EET installs may reorder or modify 2DA tables.  
**Solution:**  
- Auto‑detect MONK and KENSAI columns  
- Auto‑detect weapon row ranges  
- Zero obsolete rows dynamically  

### **3. Compatibility With Large Mod Stacks**
**Challenge:** Many mods rewrite weapon proficiencies or item usability.  
**Solution:**  
- Avoid rewriting stats or descriptions  
- Patch only usability flags and proficiency tables  
- Provide clear load‑order guidance  

---

## Results & Impact

- Stable, predictable weapon usability overhaul  
- Fully compatible with BGEE, BG2EE, and EET  
- Safe for large mod stacks and long‑term playthroughs  
- Translation support for **9 languages**  
- Clean, maintainable codebase with a `/dev` folder for modders  
- Positive reception from the Baldur’s Gate modding community  

---

## What I Learned

- Advanced WeiDU scripting and modular patch design  
- Clean 2DA table manipulation and auto‑detection techniques  
- Designing compatibility‑focused mods for large ecosystems  
- Managing translations and community contributions  
- Structuring a mod for long‑term maintainability  

---

## License

Weapons Reforged is licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.  
You may use, modify, and redistribute the mod with proper attribution.

Full license text: https://creativecommons.org/licenses/by/4.0/

