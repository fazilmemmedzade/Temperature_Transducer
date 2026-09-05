# 🌡️ Honey Degrees

**Honey Degrees** is a lightweight Windows desktop temperature conversion application built with **C# and Windows Forms**.

The application provides a simple and clean interface for converting temperatures between **Celsius (°C), Fahrenheit (°F), and Kelvin (K)**. Users can enter a temperature in any supported unit and instantly see the corresponding values in the other units.

## ✨ Features

### 🌡️ Temperature Conversion

Honey Degrees supports conversion between three commonly used temperature scales:

* **Celsius (°C)**
* **Fahrenheit (°F)**
* **Kelvin (K)**

Select the desired temperature unit, enter a value, and the application automatically calculates the equivalent values for the other units.

### 🔄 Real-Time Conversion

Temperature values are updated automatically while entering a value.

For example, when Celsius is selected:

```text
°C → °F
°C → K
```

When Fahrenheit is selected:

```text
°F → °C
°F → K
```

When Kelvin is selected:

```text
K → °C
K → °F
```

### ⌨️ Input Validation

The application includes input validation to help prevent invalid temperature values.

The input field supports:

* Numeric values
* Decimal values
* A single decimal separator
* Clipboard paste validation
* Prevention of invalid characters

### 📋 Copy Results

Each converted temperature can be copied directly to the clipboard.

There is also an option to copy all calculated values together.

Example:

```text
Honey Degrees, °F : 86 ; °C : 30 ; K : 303.15
```

### 🖥️ Custom Window Interface

Honey Degrees uses a customized Windows Forms interface rather than relying entirely on the default Windows form appearance.

The application includes:

* Custom window controls
* Minimize functionality
* Exit functionality
* Custom title/interface elements
* Draggable application window
* Information popup

### ℹ️ Information

An information window is available directly from the application interface to provide additional information about the application.

## 🧮 Conversion Formulas

Honey Degrees uses the standard temperature conversion formulas.

### Celsius → Fahrenheit

```text
°F = (°C × 1.8) + 32
```

### Celsius → Kelvin

```text
K = °C + 273.15
```

### Fahrenheit → Celsius

```text
°C = (°F - 32) / 1.8
```

### Kelvin → Celsius

```text
°C = K - 273.15
```

The remaining conversions are calculated through Celsius.

## 🛠️ Technologies

The project is built using:

* **C#**
* **Windows Forms**
* **.NET Framework 4.8.1**
* **System.Drawing**
* **System.Windows.Forms**

The project targets:

```text
.NET Framework 4.8.1
```

## 🚀 Getting Started

### Requirements

To build and run Honey Degrees, you need:

* Windows
* .NET Framework 4.8.1
* Visual Studio 2022 or newer

### Clone the Repository

```bash
git clone https://github.com/fazilmemmedzade/Temperature_Transducer.git
```

Open the solution:

```text
TemperatureTransducer.sln
```

Then build and run the project using Visual Studio.

## 📖 Usage

### 1. Select a Temperature Unit

Choose one of the available units:

```text
°C    °F    K
```

The selected unit becomes the input temperature scale.

### 2. Enter a Temperature

Enter a numeric temperature value into the input field.

The application automatically calculates the equivalent temperatures.

### 3. Copy a Result

Use the copy buttons next to the calculated values to copy an individual result.

Alternatively, copy all temperature values at once.

## 📁 Project Structure

```text
Temperature_Transducer/
│
├── Properties/
├── Resources/
│
├── Information_Popup.cs
├── Information_Popup.Designer.cs
├── Information_Popup.resx
│
├── Temperature_Transducer.cs
├── Temperature_Transducer.Designer.cs
├── Temperature_Transducer.resx
│
├── Program.cs
├── App.config
├── TemperatureTransducer.csproj
├── TemperatureTransducer.sln
└── README.md
```

## 🎯 Project Purpose

Honey Degrees was created as a simple desktop utility for quickly converting temperatures between different measurement systems.

The project focuses on keeping the interface simple while providing:

* Fast temperature conversion
* Input validation
* Clipboard support
* A custom Windows Forms interface
* Easy access to temperature information

It is a small project designed to demonstrate desktop application development with **C# and Windows Forms**.

## 👨‍💻 Author

**Fazil Məmmədzadə**

<a href="https://github.com/fazilmemmedzade">Github</a>
<a href="https://fazilmemmedzade.github.io/Portfolio">Portfolio</a>

---

<img src="https://github.com/fazilmemmedzade/Temperature_Transducer/blob/main/Annotation%202026-06-30%2008371333.png" alt="Honey Degrees" width="1000"/>
