# Forensic Tool

## Project Overview

The Forensic Tool is a robust and versatile application designed to perform thorough forensic scans of both network and system environments. This tool provides critical insights into system metadata, network interfaces, and potential security threats by monitoring network changes and analyzing system logs. The project combines advanced scanning capabilities with a user-friendly graphical interface, making it an essential tool for IT professionals, network administrators, and cybersecurity experts.

## Features

### Standalone System Scan
- **System Metadata Collection**: Gathers comprehensive details about the operating system, hardware specifications, and user information.
- **User-Friendly Display**: Presents scan results in an easy-to-read format within the GUI.

### Network Scan
- **IP Monitoring**: Continuously monitors public IP address changes to detect network hopping events.
- **Geolocation Data**: Fetches and displays geographical information of detected IP addresses.
- **Email Alerts**: Sends automatic email notifications when network hopping is detected.

### Full PC Scan
- **Comprehensive Analysis**: Integrates standalone system scans and network scans to provide a detailed overview of the system.
- **Network Interface Check**: Examines all network interfaces for unusual activity.
- **System Logs and Processes**: Analyzes system logs and running processes for potential security threats.
- **PDF Reporting**: Saves scan results in a structured PDF format for future reference.

## Technology Stack

- **Python**: Core programming language.
- **Tkinter**: Used for creating the graphical user interface.
- **Requests**: For making HTTP requests to fetch IP and location information.
- **Smtplib**: For sending email alerts.
- **PyPDF2**: For creating and managing PDF reports.

## Installation and Setup

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/yourusername/forensic-tool.git
    cd forensic-tool
    ```

2. **Install Dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

3. **Run the Application**:
    ```sh
    python maincode.py
    ```

## Usage

- **Launch the Application**: Start the application and use the GUI to select the type of scan you want to perform.
- **View Results**: Display the results directly in the application interface.
- **Save Reports**: Save the scan results as a PDF for future reference.
- **Network Monitoring**: The application will automatically monitor for network changes and send email alerts if any network hopping is detected.

## Screenshots

1. **Main Interface**:
   ![Main Interface](path-to-screenshot-main-interface)

2. **Standalone System Scan**:
   ![Standalone Scan](path-to-screenshot-standalone-scan)

3. **Network Scan**:
   ![Network Scan](path-to-screenshot-network-scan)

4. **Full PC Scan**:
   ![Full PC Scan](path-to-screenshot-full-pc-scan)

## Contributing

Contributions are welcome! Please fork the repository and submit pull requests for review. Make sure to adhere to the coding standards and include appropriate tests with your submissions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
