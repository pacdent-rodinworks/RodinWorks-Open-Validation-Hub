# RodinWorks Open Validation Hub

A community-driven, open, and non-compensated validation ecosystem for dental 3D printing.  
This repository enables dentists, dental labs, engineers, and hobbyists to collaboratively validate **Rodin resins, Ackuretta printers**, and other open-system 3D printing workflows.

Our mission:  
**Build the world’s most transparent, accurate, and community-maintained validation library for dental 3D printing.**

---

# 🚀 Quick Start — How to Use This Hub

Whether you're a **dental lab**, **clinic**, **printer user**, or **engineer**, here’s how to start:

## ▶️ **If you want to download validated settings**
1. Go to the `/Resins/` or `/Printers/` folder  
2. Open the resin/printer you’re interested in  
3. Download:
   - Print profiles (`.sol`, `.pwmx`, `.ini`)
   - Validation reports (`.md`)
   - Accuracy tables (`User-Tests.csv`)  
4. Import the profiles into your slicer or printer  
5. Follow the notes (recommended exposure, layer height, post-curing, etc.)

## ▶️ **If you want to submit your own validation**
1. Click **Issues → New Issue**
2. Select **Validation Submission**
3. Upload:
   - Your profile  
   - Photos  
   - Results  
   - STL / CSV  
4. Maintainers will review and tag it:
   - **Community Validated**
   - **Officially Verified** (if manufacturer-reviewed)

OR submit a **Pull Request** adding files to:
/Resins/<your resin>/
/Printers/<your printer>/

## ▶️ **If you're a manufacturer / institution**
You can:
- Publish official verification data  
- Upload resin–printer validation packs  
- Certify community results  
- Share research-grade test models / files  

---

## 🔍 What This Project Is

This project blends **Crowd-Sourced** real-world testing with **True Open Source** contributions.

### **Crowd-Sourced**
Users submit real test results such as:
- Print success/failure data  
- Exposure settings  
- Accuracy (mm deviation)  
- Surface finish  
- Printer/environment conditions  

### **Open Source**
Validated profiles and data are shared under **CC BY-SA 4.0**, allowing:
- Use  
- Modification  
- Redistribution  
- Forking  

As long as attribution + share-alike are preserved.

---

## 🎯 Goals
- Create a searchable library of resin–printer compatibility  
- Reduce wasted resin and failed prints  
- Enable open, repeatable, scientific validations  
- Provide manufacturers a community-backed validation channel  
- Support dental education and CE programs  

## 🗂 Repository Structure
```
/Resins/
  /Rodin-Sculpture-2.0/
    Ackuretta-SOL_95um.sol
    Validation-Report.md
  /Experimental/

/Printers/
  /Ackuretta-SOL/
    User-Tests.csv
  /DENTIQ/

/Templates/
  Test-Submission.md
  Validation-Checklist.pdf

CHANGELOG.md
CONTRIBUTING.md
README.md
LICENSE
```


## 🧪 How to Contribute

1. **Fork** this repository  
2. Add your files under the appropriate folder  
3. Use the template in `/Templates/Test-Submission.md`  
4. Submit a Pull Request  
5. Community + maintainers will review  
6. Contributions will be tagged as:  
   - **Community Validated**  
   - **Officially Verified** (if confirmed by Rodin/Ackuretta)

---

## ⚠️ Compliance & Safety
- Do **NOT** upload patient-identifiable data  
- All results are for **research, testing, and educational purposes**  
- Follow ISO 10993 / FDA guidelines for clinical use  
- All printer/resin modifications must be used responsibly  

---

## 👥 Maintainers
RodinWorks Team  
Community Contributors  
Open-Source Dental Printing Community

---

## 📬 Contact
For questions or collaboration:  
**it@pac-dent.com**

---

Let’s build the most accurate and transparent dental 3D printing validation library—together.


