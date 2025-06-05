Illsearch - GUI Reconnaissance Framework

This repository showcases the projects I have developed. Below is a detailed overview of Illsearch.

---

## Illsearch - GUI Reconnaissance Framework

**Status:** Actively Developed | **Source Code:** Private/Proprietary

Illsearch is an extensible, multi-threaded GUI framework designed to streamline network reconnaissance and security analysis. It provides a user-friendly interface for powerful command-line tools, bridging the gap between complex terminal operations and the need for a fast, visual workflow.

### Live Demonstration (GIF)

![Illsearch Demo](https://github.com/Illestonline/my-software-projects/raw/main/illsearch-demo.gif)

### About The Project & Vision

Illsearch began as a project to simplify the reconnaissance workflow. The core philosophy is to create a central hub for the initial stages of a security assessment or network analysis.

This tool is designed as an **evolving framework**. While its current foundation is built on robust Nmap integration and multi-threaded performance, Illsearch is being actively developed to incorporate a wider suite of security tools, with a roadmap focused on advanced data visualization and broader coverage of the ethical hacking lifecycle.

### Key Features

*   **Intuitive GUI:** A clean and responsive user interface built with Python's native Tkinter library.
*   **Comprehensive Nmap Scanning:** Access a wide range of Nmap scan types from a simple dropdown.
*   **Multi-threaded Architecture:** Network scans run on a separate thread, ensuring the GUI never freezes.
*   **Automated Info-Gathering:** Automatically performs `whois` and reverse DNS lookups.
*   **Smart Privilege Handling & Dependency Checking:** Provides a smooth user experience across different operating systems.
*   **Advanced Result Management:** Features include a "Clean Output" filter and the ability to export scan results.

### Technologies Used

*   **Backend:** Python
*   **GUI:** Tkinter
*   **Concurrency:** Python `threading` module
*   **System Integration:** `subprocess`, `shutil`, `platform` modules
*   **Core Tooling:** Nmap (wrapper), whois (wrapper)

---
*For inquiries or to request a private demonstration, please contact me at [ianryansmith@gmail.com].
