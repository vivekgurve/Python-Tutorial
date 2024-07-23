# Python Installation Guide for Windows

This guide provides step-by-step instructions on how to install Python on a Windows operating system.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Step 1: Download Python](#step-1-download-python)
- [Step 2: Install Python](#step-2-install-python)
- [Step 3: Verify Installation](#step-3-verify-installation)
- [Step 4: Setting Up Environment Variables](#step-4-setting-up-environment-variables)
- [Step 5: Installing Packages with pip](#step-5-installing-packages-with-pip)
- [Conclusion](#conclusion)

## Prerequisites

Before you start, ensure that you have administrative access to your Windows computer.

## Step 1: Download Python

1. Open your web browser and go to the official Python website: [https://www.python.org/](https://www.python.org/).
2. Navigate to the Downloads section.
3. Click on the download link for the latest version of Python for Windows.

## Step 2: Install Python

1. Locate the downloaded Python installer file (usually in your Downloads folder).
2. Double-click the installer file to start the installation process.
3. In the installer window, check the box that says "Add Python to PATH". This is crucial for running Python from the command line.
4. Click on "Install Now" to begin the installation.
5. Wait for the installation to complete. This may take a few minutes.

## Step 3: Verify Installation

1. Open the Command Prompt. You can do this by searching for "cmd" in the Start menu and pressing Enter.
2. In the Command Prompt, type the following command and press Enter:
   ```sh
   python --version
   
## Step 4: Setting Up Environment Variables

If you checked the "Add Python to PATH" option during installation, you can skip this step. If not, follow these instructions:

1. Right-click on the Start button and select "System".
2. Click on "Advanced system settings".
3. In the System Properties window, click on the "Environment Variables" button.
4. In the Environment Variables window, scroll down and find the "Path" variable under the "System variables" section, then click "Edit".
5. Click "New" and add the path to your Python installation. The default path is usually C:\Python39 or similar, depending on the version.
6. Also, add the path to the Scripts directory, e.g., C:\Python39\Scripts.
7. Click "OK" to save the changes.

   
