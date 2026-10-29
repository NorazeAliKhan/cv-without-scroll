# Noraze Khan — Interactive CV Portfolio (No-Scroll View)

A zero-scroll, executive dashboard portfolio website for **Noraze Khan**, preserving the design colors, typography, assets, and clean student portrait image from the original design system.

---

## 🎯 What is the "No-Scroll" Architecture?

Unlike traditional long web pages that require scrolling down to read sections:
- **Zero Page Scroll**: The browser window remains locked in place (`overflow: hidden` on viewport / `h-screen`).
- **Interactive View Switcher**: High-performance tabs switch between **Overview**, **About**, **Skills**, **Projects**, **Education**, **Certifications**, and **Contact** with smooth animated transitions.
- **Persistent Profile Sidebar**: On desktop, Noraze's clean student portrait, credentials, university details, and direct contact buttons remain anchored on the left.
- **Keyboard Navigation**: Press **`[←]` / `[→]`** arrow keys or numbers **`[1]` - `[7]`** to navigate between sections instantly.

---

## 🚀 How to Run and View

### Option 1: Direct File Launch (Fastest)
Double-click `index.html` in File Explorer or run in PowerShell:
```powershell
Start-Process "c:\Users\DELL\Desktop\cv without scroll\index.html"
```

### Option 2: Local HTTP Server
Run the included PowerShell server script:
```powershell
powershell -ExecutionPolicy Bypass -File .\serve.ps1
```
This opens `http://localhost:8080/` in your default browser.

---

## 🎨 Preserved Design Elements & Assets

- **Colors**:
  - Deep Navy Blue (`#14213D` / `#000A24`)
  - Professional Blue (`#0051D5` / `#2563EB`)
  - Teal Accent (`#049A87` / `#83F6E0`)
  - Off-white canvas (`#F8F9FF`) and elevated white cards (`#FFFFFF`)
- **Student Portrait**:
  - `student-profile.jpg` (High-resolution, clean student photo without any text or watermark).
- **Project SVGs**:
  - Fixora (Connected node architecture)
  - AI Interior Design (Isometric room wireframe)
  - University Portal (Academic dashboard structure)
- **All CV Details**:
  - Degree: BS Computer Science, Qarshi University
  - Semester: 7th | Expected: 2027 | Current CGPA: 2.91/4.00
  - All 6 skill categories & technologies
  - Both Coursera Certifications (AI & Web Development)
  - Functional Email (`norazekha01@gmail.com`) and GitHub links (`https://github.com/NorazeAliKhan`)
