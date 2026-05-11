# Remote Imaging Server — 148th Air National Guard

The Remote Imaging Server project modernized and expanded the imaging capabilities of the 148th Air National Guard, enabling administrators to reimage computers anywhere on the network using a standardized USAF Windows image. The system also automated domain‑joining, dramatically reducing manual workload and improving operational efficiency across multiple bases.

This project demonstrates my ability to design, deploy, and document enterprise‑grade infrastructure with real‑world impact at scale.

---

## Project Overview

The Remote Imaging Server allows authorized administrators to remotely reimage any computer on the base network using a custom USAF‑approved Windows image. After imaging, the system automatically joins the machine to the domain with no additional steps required.

This capability is critical for:

- Sensitive or restricted areas where IT staff cannot physically access devices  
- Distributed facilities where transporting systems is inefficient  
- Standardizing workstation deployments across the Air National Guard  

The project replaced an outdated Windows Server 2012 system that could only image machines locally and required manual domain‑joining.

---

## My Role

As a **GS‑11 IT Specialist**, I was responsible for the full lifecycle of the upgrade:

- Identified and procured replacement server hardware  
- Completed funding and acquisition paperwork  
- Purchased and installed Windows Server 2019  
- Configured the server as a fully functional remote imaging system  
- Automated domain‑joining to eliminate manual admin steps  
- Authored a comprehensive imaging guide for other USAF bases  

This guide became the standard reference for multiple bases building their own imaging servers.

---

## Tools & Technologies

- **Server Hardware** — procurement, configuration, deployment  
- **Windows Server 2019** — OS installation, imaging services, automation  
- **Custom USAF Windows Image** — standardized workstation deployment  
- **Snipping Tool / PowerPoint** — documentation and visual guide creation  

---

## Key Features

- **Remote imaging across the entire network** (not just local subnet)  
- **Automatic domain‑joining** after imaging  
- **Standardized USAF Windows image deployment**  
- **Clear, step‑by‑step imaging guide for other bases**  

---

## Technical Challenges & Solutions

### **1. Local‑only imaging limitations**
The old system could only image machines physically connected to the server.

**Solution:**  
Configured the new server to support full network‑wide imaging, enabling remote deployment anywhere on base.

---

### **2. Manual domain‑joining**
Admins previously had to manually join each imaged machine to the domain.

**Solution:**  
Automated domain‑joining using a secure service account, eliminating repetitive manual work.

---

### **3. Lack of documentation**
The previous imaging process was unclear, inconsistent, and difficult for new admins to follow.

**Solution:**  
Created a detailed, visual Remote Imaging Guide used by dozens of USAF bases.

---

## Results & Impact

- Adopted by **dozens of USAF bases worldwide**  
- Helped image **tens of thousands of computers**  
- Reduced man‑hours by eliminating manual domain‑joining  
- Enabled imaging in **sensitive or restricted areas** without IT staff present  
- Allowed local admins to reimage systems immediately, reducing downtime  
- Standardized workstation deployment across multiple installations  

This project delivered massive operational efficiency gains and became a widely used resource across the Air National Guard.

---

## What I Learned

- How to procure and deploy enterprise server hardware  
- Installing and configuring Windows Server 2019 for imaging  
- Automating domain‑joining using service accounts  
- Writing clear, scalable documentation for large organizations  
- Designing infrastructure that supports distributed, secure environments  

