# Encryptify: A File Encryptor and Decryptor
A secure file encryption and decryption tool written in C++, utilizing advanced synchronization mechanisms like semaphores and locks to ensure data integrity and safety.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Code Structure](#code-structure)
- [Usage](#usage)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)
- [Developer](#developer)

## Introduction
**Encrypty** is a robust file encryption and decryption application designed to secure sensitive data. Leveraging C++’s capabilities, the application efficiently manages file operations with multithreading, ensuring that encryption and decryption processes are both secure and efficient. The application implements semaphores and locks to coordinate access to shared resources, preventing data corruption.

## Features
- **File Encryption/Decryption:** Securely encrypts and decrypts files using strong algorithms.
- **Multithreading Support:** Handles multiple file operations simultaneously, optimizing performance.
- **Synchronization Mechanisms:** Implements semaphores and locks for safe access to shared resources.
- **User-Friendly Command-Line Interface:** Simple and intuitive command-line options for ease of use.
- **Configurable Settings:** Users can modify encryption parameters according to their requirements.

## Technologies Used
- C++
- Multithreading
- Semaphores and Locks
- Command-Line Interface (CLI)
- Makefile for build automation

## Getting Started

### Prerequisites
- C++ Compiler (e.g., g++)
- CMake (for building)
- Basic knowledge of C++ and command-line operations

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/encrypty.git
   cd encrypty
2. Compile the application using the Makefile
  make

## Running the Application
To run the encryption application, use the following command :
./encrypty --encrypt <input_file> <output_file>

To decrypt a file, use:
./encrypty --decrypt <input_file> <output_file>
Replace <input_file> and <output_file> with the paths to your files.

## Code Structure
encrypty/
├── .idea/               # IDE configuration files
├── .vscode/             # Visual Studio Code configuration files
├── src/                 # Source files
│   ├── main.cpp         # Main application logic
│   └── app/             # Application specific logic
├── .env                 # Environment variables configuration
├── .gitignore           # Files to ignore in Git
├── Makefile             # Build instructions
└── makeDirs.py          # Script to create necessary directories

