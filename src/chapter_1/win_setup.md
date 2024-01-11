# Windows Setup

## NodeJS

Setting up Node.js on Windows and adding it to the environment variables involves the following steps:

1. Download Node.js Installer:

   - Visit the official Node.js website at _<https://nodejs.org/>_.
   - Download the recommended version for Windows (LTS is recommended for most users).
   - Run the downloaded installer.

2. Install Node.js:

   - Double-click on the downloaded `.msi` file to start the installation process.
   - Follow the on-screen instructions to install Node.js. By default, the installer will set up both Node.js and npm (Node Package Manager).

3. Add Node.js to Environment Variables:

    To use Node.js and npm from any command prompt or terminal window, you need to add them to the system's PATH environment variable.

    1. Find Node.js Installation Path:

       - The default installation path for Node.js on Windows is `C:\Program Files\nodejs\`.

    2. Add to PATH:

        - Right-click on the Start button and select System (or search for System in the search bar and select it).
        - Click on Advanced system settings on the left side.
        - Click on the Environment Variables button.
        - Under the System Variables section, find and select the Path variable, then click Edit.
        - Click New and then paste the path to the Node.js installation directory (e.g., `C:\Program Files\nodejs\`).
        - Click OK to close each of the windows.

4. Verify Node.js and npm from Any Directory:

   - Open a new Command Prompt (cmd) window.
   - Type `node -v` and press Enter to verify Node.js.
   - Type `npm -v` and press Enter to verify npm.
   - Now, Node.js and npm should be accessible from any directory in the command prompt, and you're ready to start developing with Node.js on Windows!

## Visual Studio Code

To install Visual Studio Code (VS Code) on Windows, follow these steps:

- Visit the official Visual Studio Code website at _<https://code.visualstudio.com/>_.
- Click on the Download for Windows button to download the installer.
- Then follow the install wizard.
