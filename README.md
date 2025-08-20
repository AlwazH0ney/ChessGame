# ChessGame
C# WPF chess game (ChessUI + ChessLogic) built for SWE40006. Packaged with WiX (MSI) and an optional MSIX sideload bundle. Download installers from Releases.
# Chess Game (C# · WPF · .NET 6)

A simple chess game built in C# for the SWE40006 unit. The UI project **ChessUI** renders the board and handles input; a small library **ChessLogic** checks basic moves. The project focuses on Windows deployment with a classic **WiX MSI** installer and an optional **MSIX** sideload package.

> **Download:** get the latest installer from **Releases**  
> https://github.com/<your-username>/<your-repo>/releases/latest

---

## ✨ Features
- 8×8 chessboard UI (WPF)
- Basic legal moves (king, queen, rook, bishop, knight, pawn)
- Start menu shortcut via MSI
- Two packaging styles:
  - **MSI (WiX)** → installs to *C:\Program Files\Chess Game* + Start menu shortcut
  - **MSIX (sideload)** → modern packaging for testing

---

## 🧩 Projects in this repo
