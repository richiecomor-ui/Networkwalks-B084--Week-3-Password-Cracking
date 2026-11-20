# Networkwalks -- Week 3 Cybersecurity Project

## Password Cracking with Johnny and John the Ripper

[Cybersecurity](https://img.shields.io/badge/Field-Cybersecurity-red) [Tools](https://img.shields.io/badge/Tools-John_the_Ripper-blue) [Training](https://img.shields.io/badge/Program-Networkwalks-green)

## Project Overview

This repository documents my Week 3 practical cybersecurity project as part of the Networkwalks Cybersecurity Training Program (Batch B084).

The project focuses on password auditing and recovery techniques using Johnny (the graphical user interface for John the Ripper) and NetworkWalks Hash Calculator.

The exercise explores how password hashes can be extracted from password-protected PDF documents and prepared for authorized password recovery attempts.

## Project Objectives

- Understand the fundamentals of password security and password auditing.
- Learn how password-protected PDF documents are secured.
- Extract PDF password hashes using NetworkWalks Hash Calculator.
- Install and configure Johnny.
- Connect Johnny to the John the Ripper executable.
- Understand the process of password recovery using John the Ripper.
- Document practical activities and observations.

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Windows | Operating system used for the practical |
| NetworkWalks Hash Calculator | PDF password hash extraction |
| Johnny | Graphical interface for John the Ripper |
| John the Ripper 1.9.0 Jumbo | Password auditing and recovery engine |
| Command Prompt | Testing the John the Ripper executable |
| GitHub | Project documentation and evidence storage |

## Activities Performed

### 1. Downloading and Installing John the Ripper

Downloaded John the Ripper 1.9.0 Jumbo for Windows 64-bit.

Extracted the downloaded ZIP package and located the `run` folder containing the `john.exe` executable.

Verified the installation by running:

`john.exe --help`

The help information displayed successfully, confirming that the executable was working.

### 2. Installing and Configuring Johnny

Located the separate Johnny GUI installation package and installed the application.

Opened Johnny and navigated to Settings.

Used the Browse option to locate and select the existing John the Ripper executable.

Executable path:

`C:\Users\LENOVO\Downloads\john-1.9.0-jumbo-1-win64\run\john.exe`

Johnny successfully recognized the John the Ripper installation.

### 3. Obtaining the Encrypted PDF

Obtained the instructor-provided password-protected PDF document:

`My Locked PDF1.pdf`

The document was used as the sample file for the password auditing exercise.

### 4. PDF Hash Extraction Using NetworkWalks

Accessed NetworkWalks Hash Calculator and selected the PDF hash extraction functionality.

Uploaded the instructor-provided encrypted PDF and successfully generated its PDF-specific password hash.

Copied the extracted hash for use in the subsequent password recovery exercise.

### 5. Password Recovery Preparation

Prepared to use Johnny with the John the Ripper engine for password recovery attempts.

The objective of this stage was to use the extracted PDF hash in an authorized password auditing exercise and examine the recovery process.

**Note:** Successful password recovery has not yet been verified in the available practical evidence.

## Evidence Collected

Screenshots documenting the practical exercise include:

- John the
