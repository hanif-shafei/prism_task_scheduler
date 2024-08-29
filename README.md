# prism_task_scheduler

This private repository is dedicated to tracking and saving changes for files exported from Windows Task Scheduler, specifically for tasks related to Symfony-based applications.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

Windows Task Scheduler allows users to automate tasks on their Windows systems. This repository helps in maintaining a version-controlled history of exported task files, ensuring that changes are tracked and documented effectively. The tasks in this repository are specific to Symfony-based applications.

## Getting Started

### Prerequisites

- Windows operating system
- Access to Windows Task Scheduler
- Git installed on your system
- Symfony-based application

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/hanif-shafei/prism_task_scheduler.git
    ```
2. Navigate to the repository directory:
    ```bash
    cd prism_task_scheduler
    ```

## Usage

### Exporting Tasks

1. Open Task Scheduler.
2. Select the task you want to export.
3. Click on "Export" in the right-hand Actions pane.
4. Save the file to your desired location.

### Importing Tasks

1. Open Task Scheduler.
2. Click on "Import Task" in the right-hand Actions pane.
3. Browse to the location of the exported task file.
4. Select the file and click "Open".
5. Review the task settings and click "OK" to import.

### Adding Exported Files to the Repository

1. Add the exported file to the repository:
    ```bash
    git add path/to/your/exported/file.xml
    ```

2. Commit the changes:
    ```bash
    git commit -m "Add exported task file for Symfony app"
    ```

3. Push the changes to the repository:
    ```bash
    git push origin main
    ```

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Make your changes.
4. Commit your changes:
    ```bash
    git commit -m "Describe your changes"
    ```
5. Push to the branch:
    ```bash
    git push origin feature/your-feature-name
    ```
6. Open a pull request.

---
