# CMEOfflineKit

CMEOfflineKit is a comprehensive tool designed to simplify the offline installation of the Common Malware Environment (CME) and all its associated libraries and packages. This tool allows users to set up CME, along with Python and its necessary dependencies, without requiring an internet connection. Ideal for testing purposes, CMEOfflineKit ensures that all the components of the CME framework are available locally, enabling seamless installation and operation in environments where internet access is restricted or unavailable.

## Key Features

- **Offline Installation**: Install CME and all required libraries, including Python, without an internet connection.
- **Complete Setup**: Includes all necessary packages and dependencies for running CME, ensuring a hassle-free installation process.
- **Testing Ready**: Provides a ready-to-use environment for malware analysis and testing with CME, even in isolated or secure environments.

## Warning
Windows Defender may detect some of the packages included in CMEOfflineKit as potentially harmful and could automatically delete them or trigger alerts. Please ensure that you have the necessary legal permissions and are in compliance with all relevant policies before proceeding with the installation.


# How to Extract CMEOfflineKit

Follow these steps to extract the CMEOfflineKit archive using 7-Zip:

## Step 1: Install 7-Zip
If you don’t already have 7-Zip installed, download and install it from [7-Zip's official website](https://www.7-zip.org/).

## Step 2: Gather All Split Files
Ensure you have all parts of the split archive in the same folder. The files will typically be named something like:
- `CMEOfflineKit.zip.001`
- `CMEOfflineKit.zip.002`

## Step 3: Extract the Split Archive
1. Right-click on the first part of the split archive (e.g., `CMEOfflineKit.zip.001`).
2. From the context menu, select **7-Zip > Extract Here** (or **Extract to "CMEOfflineKit"** to create a new folder).
3. 7-Zip will automatically detect the other parts (e.g., `.002`, `.003`, etc.) and combine them during extraction.
4. The extraction process will begin, and 7-Zip will combine all parts into the original files or folder.

## Step 4: Check the Extracted Files
Once extraction is complete, you should see the extracted files in the same location or in the newly created folder. If everything was extracted correctly, you can open and use the files as needed.

# Usage

Follow these steps to set up CMEOfflineKit:

## Step 1: Unzip the Files
Unzip the downloaded CMEOfflineKit archive to a folder of your choice.

## Step 2: Run `python.exe`
Navigate to the folder where the files were extracted and run `python.exe` from the folder.

## Step 3: Run `Set Up Python Env.bat`
Next, run the `Set Up Python Env.bat` file to set up the Python environment and install the necessary dependencies.

## Step 4: Run `installer.py`
After setting up the environment, run the `installer.py` script to complete the installation of CME and its components.

## Step 5: Verify CME Installation
To check if CME is installed correctly, run the following commands:
- `python cme --version`
- `cme -h`

These commands will confirm that CME is properly installed and provide the available options.


