This project is developed for Malin Space Science Systems (MSSS) as part of the Astronomical Processing Project. The solution replaces the existing socket-based system with a modern Inter-Process Communication (IPC) design using Windows Communication Foundation (WCF) with Named Pipes.

The system provides astronomical calculation services via a server console application, a WinForms client application, and a custom third-party library (AstroMath.DLL).

🚀 Project Components

AstronomicalProcessingServer

A continuously running .NET Console Application.

Exposes astronomical calculation services via WCF (Named Pipes).

References the AstroMath.DLL for all scientific calculations.

AstronomicalProcessingClient

A WinForms Application (.NET Framework) that connects to the server.

Provides input fields for each calculation.

Displays validated, scientific-format results in read-only textboxes.

Includes multi-language support (English, French, German).

Supports runtime UI customisation (theme, background colour, font).

AstroMath.DLL

A custom-built third-party library containing four astronomical functions:

Star Velocity

Star Distance

Temperature Conversion (Celsius ↔ Kelvin)

Blackhole Event Horizon

⚙️ Features

✅ Inter-Process Communication via WCF Named Pipes.

✅ Multi-language runtime switching (English, French, German).

✅ UI customisation – Day/Night modes, custom colours, custom fonts.

✅ Error validation on all inputs with range checks.

✅ Scientific format outputs for accurate astronomical values.

✅ Agile development tracked in GitHub Kanban.

📂 Repository Structure
AstronomicalProcessingProject/
│
├── AstronomicalProcessingServer/     # Console Server Application
├── AstronomicalProcessingClient/     # WinForms Client Application
├── AstroMath/                        # Custom DLL Project
│   └── AstroMath.dll
├── docs/                             # Documentation, diagrams, templates
└── README.md                         # Project overview

🛠️ Installation & Setup
Prerequisites

Windows OS

.NET Framework (4.7.2 or later recommended)

Visual Studio 2022

Steps

Clone this repository:

git clone https://github.com/<your-username>/AstronomicalProcessingProject.git


Open the solution in Visual Studio.

Build the solution to generate AstroMath.DLL.

Start the AstronomicalProcessingServer (Console App).

Run the AstronomicalProcessingClient (WinForms App).

Connect client → server, input data, and calculate results.

📊 Agile & Version Control

GitHub repository uses Kanban Project Board for Agile workflow:

To Do → In Progress → Testing → Done

Development follows iterative sprints for modular feature delivery.

Version history is maintained through Git commits and branches.

🌍 Future Enhancements

Expansion to Eastern Europe, Asia, and Canada.

Additional astronomical calculations in AstroMath.DLL.

Extended licensing support for third-party organisations.

📜 License

This project and its custom DLL (AstroMath.DLL) are developed for MSSS with potential licensing for third-party organisations.
