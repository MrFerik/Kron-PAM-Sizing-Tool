# Kron-PAM-Sizing-Tool
The Kron PAM Sizing Tool is a web-based application designed to help users estimate the system requirements (RAM, CPU, Disk space) for the Kron Privileged Access Management (PAM) solution. It provides recommendations based on the number of active sessions, deployment type (All-in-One or Distributed), and whether High Availability (HA) is enabled.

# Kron PAM Sizing Tool

The **Kron PAM Sizing Tool** helps users determine the appropriate system resources (RAM, CPU, Disk space) for deploying the Kron Privileged Access Management (PAM) solution. This tool calculates the necessary resources based on the number of active sessions, deployment type (All-in-One or Distributed), and High Availability (HA) configuration.

## Features

- Provides estimated system requirements (RAM, CPU, Disk) based on user input.
- Supports different deployment types: All-in-One and Distributed.
- High Availability (HA) options to ensure redundancy and fault tolerance.
- Automatically updates resource recommendations as the number of active sessions is adjusted via a slider.

## How to Use

1. **Open the Tool**: Go to the GitHub Pages link or open the HTML file directly in your browser.
2. **Choose Deployment Type**: Select either "All-in-One" or "Distributed Deployment".
3. **Adjust the Number of Sessions**: Use the slider to select the number of active sessions.
4. **Enable/Disable HA**: If you're using a distributed deployment, choose whether to enable or disable High Availability.
5. **View Recommendations**: The tool will display the recommended system resources for your selected configuration.

## Files Included

- `index.html`: Main HTML file with the user interface.
- `styles.css`: Styling for the tool's page layout.
- `script.js`: JavaScript code for handling user input and calculating system requirements.


## Contributions

Feel free to submit pull requests, report issues, or provide suggestions for improvements.
