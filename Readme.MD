# GEMINI-CLI

This repository provides instructions on how to set up WSL and install the Gemini CLI.

## WSL (Windows Subsystem for Linux) Installation

1.  **Open PowerShell or Command Prompt as an Administrator.**
2.  Run the command: `wsl --install`
3.  Restart your computer.
4.  Set up your Linux distribution by creating a username and password.

## Gemini CLI Installation

1.  **Install Node.js (version 18 or higher).**
2.  Install the Gemini CLI globally using npm:
    ```bash
    npm install -g @google/gemini-cli
    ```
3.  Alternatively, you can use npx for temporary execution:
    ```bash
    npx https://github.com/google-gemini/gemini-cli
    ```
4.  After installation, run `gemini` to start the authentication process.
