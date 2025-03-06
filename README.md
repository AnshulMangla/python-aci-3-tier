README TO USE THIS PACKAGE


# Installation

## Install Python 3+

### **Windows Installation**
1. **Download Python Installer**  
   - Visit the official Python website: [https://www.python.org/downloads/](https://www.python.org/downloads/)  
   - The site will detect your OS and suggest the latest Python version. Click **Download Python 3.x.x**.

2. **Run the Installer**  
   - Open the downloaded `.exe` file.
   - **IMPORTANT:** Check the box **"Add Python to PATH"** at the bottom.
   - Click **"Install Now"** to proceed with the installation.

3. **Verify Installation**  
   - Open **Command Prompt (cmd)** and type:
     ```sh
     python --version
     ```
   - You should see the installed Python version, e.g., `Python 3.x.x`.
  
### **macOS Installation**
1. **Download Python Installer**  
   - Go to [https://www.python.org/downloads/mac-osx/](https://www.python.org/downloads/mac-osx/)  
   - Download the latest **macOS installer** (`.pkg` file).

2. **Run the Installer**  
   - Open the downloaded `.pkg` file and follow the on-screen instructions.

3. **Verify Installation**  
   - Open **Terminal** and run:
     ```sh
     python3 --version
     ```
   - If Python 3 is installed, you’ll see the version displayed.  
  
---
  
## Installing ACIToolkit (acitoolkit.acitoolkit) on Windows and macOS

### **Windows Installation**

1. **Install acitoolkit**  
   ```sh
   pip install acitoolkit
   ```

2. **Verify Installation**  
   Run the following command to ensure the package is installed correctly:
   ```sh
   python -c "import acitoolkit; print(acitoolkit.__version__)"
   ```


### **macOS Installation**

1. **Install acitoolkit**  
   ```sh
   pip3 install acitoolkit
   ```

2. **Verify Installation**  
   Run:
   ```sh
   python3 -c "import acitoolkit; print(acitoolkit.__version__)"

