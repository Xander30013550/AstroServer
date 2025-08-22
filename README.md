# 🌌 Astronomical Processing Project

**Author:** Xander Smith  
**Date:** 22/8/25  

This project is developed for **Malin Space Science Systems (MSSS)** as part of the Astronomical Processing Project. The solution replaces the existing socket-based system with a modern **Inter-Process Communication (IPC)** design using **Windows Communication Foundation (WCF)** with Named Pipes.  

The system provides astronomical calculation services via a **server console application**, a **WinForms client application**, and a custom **third-party library (AstroMath.DLL)**.  

---

## 🚀 Project Components

- **AstronomicalProcessingServer**  
  Console application that runs continuously. Provides services via WCF Named Pipes.  

- **AstronomicalProcessingClient**  
  WinForms application (.NET Framework) that connects to the server, accepts user input, displays validated results, and supports multi-language and UI customisation.  

- **AstroMath.DLL**  
  Custom-built library providing:  
  1. Star Velocity  
  2. Star Distance  
  3. Temperature Conversion (Celsius ↔ Kelvin)  
  4. Blackhole Event Horizon  

---

## ⚙️ Features

- Inter-Process Communication via WCF Named Pipes  
- Multi-language runtime switching (English, French, German)  
- UI customisation (Day/Night modes, custom background colours, custom fonts)  
- Input validation and error handling  
- Scientific notation outputs  
- Agile development tracked with GitHub Kanban  

---

## 📂 Repository Structure

