
When working with STM32 microcontrollers, the following files and folders are typically used to manage the project:

### 1. .ioc File (STM32CubeMX Configuration File)
This is one of the most important files in the project. It contains the graphical configurations for peripherals, clock settings, and pinout assignments.
* **In short:** This is the primary file where the software stores the chip's hardware configuration.

### 2. Core Folder
This folder contains the fundamental files required for the project's operation.
* **Inc (Include):** Contains the Header files (`.h`).
* **Src (Source):** Contains the Source files (`.c`), including the main logic.

### 3. main.c File
This is the file where your application's primary programming code resides. When the microcontroller powers on, it executes the `main()` function located here.
* **In short:** Your main program logic and user code are written within this file.

### 4. Drivers Folder
This folder houses the HAL (Hardware Abstraction Layer) and CMSIS libraries specific to your chip.
* **In short:** These are the drivers required to communicate with the hardware components.

---

### Project Structure Overview

| File / Folder | Description |
| :--- | :--- |
| **Project_Name.ioc** | Graphical configuration file |
| **Core/Src/main.c** | Main programming code (The heart of the app) |
| **Core/Inc** | Location for Header files |
| **Drivers** | STM32 Standard/HAL libraries |
| **Startup** | Startup code for the microcontroller (Assembly) |

