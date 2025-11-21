# CalculatorApp – .NET MAUI Mobile Application (C#)

This project is a fully functional **cross-platform Calculator application** built with **.NET MAUI**.  
It demonstrates clean UI design with XAML, MVVM-ready architecture, event handling, and reusable C# logic classes.

The app performs basic arithmetic operations and includes additional features such as clear entry, full clear, sign toggle, and percentage conversion. It runs on **Android, iOS, and Windows**.

---

## 🎯 Key Features

### 🧮 Core Calculator Operations
- Addition (+)
- Subtraction (–)
- Multiplication (×)
- Division (÷)
- Real-time expression updates
- Accurate decimal support

### ✨ Extra Functionalities
- **Clear Entry (CE)** – clears the current input  
- **Clear All (C)** – clears the entire calculation  
- **Toggle Sign (±)** – switch between positive/negative  
- **Percentage (%)** – convert values to percent  
- **Chained operations** without resetting  
- **Error handling** (division by zero)

### 📱 Modern MAUI UI
- Clean XAML layout  
- Responsive design for all screen sizes  
- Button grid with proper spacing  
- Interactive UI using event handlers  
- Works on:
  - Android (Emulator or physical device)
  - Windows Desktop
  - iOS (requires Mac)

---

## 🧰 Technologies Used

- **C#**
- **.NET MAUI**
- **XAML UI Design**
- **AppShell Navigation**
- **Models + Utility Classes (Calculator.cs, MathUtil.cs)**
- **Visual Studio 2022**
- **Cross-Platform Deployment**

---

## 📁 Project Structure

CalculatorApp/

│── CalculatorApp.sln

│── CalculatorApp/

│ ├── App.xaml

│ ├── App.xaml.cs

│ ├── AppShell.xaml

│ ├── AppShell.xaml.cs

│ ├── MauiProgram.cs

│ │

│ ├── Models/

│ │ ├── Calculator.cs # Core calculation logic

│ │ └── MathUtil.cs # Helper functions (sign toggle, percentage, etc.)

│ │

│ ├── MainPage.xaml # UI layout

│ ├── MainPage.xaml.cs # UI event handlers

│ │

│ ├── Platforms/

│ │ ├── Android/ # Platform-specific code

│ │ └── iOS/

│ │

│ └── Resources/

└── ...

---

## 🔧 How to Run the App

1. Clone the repository
2. Open the solution: Open CalculatorApp.sln in Visual Studio 2022.
3. Install MAUI workload (if needed)
4. Run on your preferred platform

Android Emulator → Run > Android
Windows → Run > Windows Machine
iOS (Mac required) → Run > iOS

---

## 🧠 What I Learned
Building a functional mobile UI using XAML
Organizing reusable logic in Models and Utility classes
Designing clean, responsive mobile layouts
Handling button events and user input in MAUI
Deploying and testing cross-platform mobile apps
Understanding mobile app lifecycle and initialization

 ---

## 🚀 Future Enhancements
Add calculation history panel
Add scientific calculator functions (sin, cos, tan, sqrt, etc.)
Create a dark/light theme toggle
Implement MVVM with data binding
Add animations for button interactions
Add sound or vibration feedback on keypress

---

## 📄 License
This project is open for educational and portfolio use.
