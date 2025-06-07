# ApexClean Pro - Your Ultimate PC Optimizer (in development)🧹

## ✨ Features

* **Comprehensive Cleaning Categories**: Target various types of junk files, including:
    * Temporary Files
    * Browser Cache (Chrome, Firefox, Edge)
    * System Logs
    * Recycle Bin
    * Thumbnail Cache
    * Windows Defender Cache
    * Old Windows Update Files
    * Program Data Cache
    * Font Cache
    * Temporary Internet Files
* **Intuitive User Interface**: A sleek, modern design built with `ttkthemes` for a polished look, offering both light and dark modes.
* **Real-time Performance Monitoring**: Keep an eye on your CPU, Memory, and Disk usage with live statistics and historical graphs.
* **Scan and Clean Functionality**: Easily scan your system for junk files and confidently remove them with detailed progress tracking.
* **Detailed Scan Log**: Review exactly what files were found and cleaned in the dedicated "Scan Details" tab.
* **Customizable Cleaning**: Select specific categories to scan and clean, giving you full control over the process.
* **Safety First**: Categories like "Recycle Bin" and "Old Windows Update Files" are highlighted for their potential impact, and a confirmation prompt before cleaning ensures you're always in control.
* **Persistent State**: Your last cleaned timestamp and category selections are saved for convenience.

## 🚀 Getting Started

### Prerequisites

Before you run ApexClean Pro, ensure you have Python installed (Python 3.7+ is recommended). You'll also need to install the necessary Python packages.

### Installation

1.  **Clone the repository (or download the source code):**

    git clone https://github.com/0xYZ/ApexClean-Pro.git
    cd ApexClean-Pro

2.  **Place the icon file:**
    Ensure `cleaner_icon.ico` is in the same directory as `ApexClean.exe` for the application icon to display correctly. A default icon is usually provided within the repository.

### Running the Application

Simply execute the `ApexClean.exe` file:

python ApexClean.exe

## 💡 Usage

1.  **PC Cleaner Tab (🧹):**
    * **Select Categories**: On the left, choose which categories of junk files you want to scan. Click on a category to see its description and impact.
    * **Start Scan**: Click the "🚀 Start Scan" button to analyze your selected categories. The progress bar and status label will update.
    * **Review Results**: After the scan, the "Scan Summary" will show the total space that can be saved.
    * **Clean Now**: Click "🧹 Clean Now" to remove the detected junk files. A confirmation prompt will appear for high-impact cleaning.

2.  **Scan Details Tab (📋):**
    * This tab provides a detailed log of the scanning and cleaning processes, showing which files were found and, if cleaned, their status.

3.  **Performance Tab (📊):**
    * Monitor your system's CPU, Memory, and Disk usage in real-time. The graphs provide a visual history of resource consumption over the last 60 seconds.

4.  **Settings Tab (⚙️):**
    * **Theme Settings**: Switch between "Light Mode" and "Dark Mode" to suit your preference.
    * **General Application Settings**: Configure options like "Run quick scan on application startup" and "Prompt for confirmation before cleaning."
    * **Cleaning Options**: Choose between "Safe Mode" (recommended) and "Aggressive Mode" for cleaning.
    * **Backup & Recovery**: Optionally enable "Create a restore point before cleaning" (Windows only).
    * **About**: View application version and developer information.

## ⚙️ Development

### Project Structure

`ApexClean-Pro/`

`├── ApexClean.exe`               # Main application logic

`├── cleaner_icon.ico`            # Application icon

`└── README.md`                   # This README file


### Technologies Used

* **Python**: The core programming language.
* **Tkinter**: Python's standard GUI library for building the desktop application.
* **ttkthemes**: Enhances Tkinter widgets with modern themes.
* **Pillow (PIL)**: Used for image manipulation (though not extensively in the provided code, good for future enhancements).
* **Matplotlib**: For creating real-time performance graphs.
* **psutil**: For accessing system details like CPU, memory, and disk usage.
* **`os`, `shutil`, `glob`, `sys`, `threading`, `time`, `webbrowser`, `json`, `ctypes`**: Standard Python libraries for file system operations, multi-threading, time tracking, opening web links, JSON serialization, and Windows API calls (DPI awareness).

## 📧 Contact

Developed by 0xYZ.
For support or inquiries: [https://guns.lol/0xYZ](https://guns.lol/0xYZ)

---

**© 2025 ApexClean Solutions. All rights reserved.**
