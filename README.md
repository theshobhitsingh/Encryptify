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
**Encryptify** is a robust file encryption and decryption application designed to secure sensitive data. Leveraging C++’s capabilities, the application efficiently manages file operations with multithreading, ensuring that encryption and decryption processes are both secure and efficient. The application implements semaphores and locks to coordinate access to shared resources, preventing data corruption.

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
   git clone https://github.com/yourusername/encryptify.git
   cd encryptify
   
2. Compile the application using the Makefile:
   ```bash
      make

## Running the Application
1. To run the encryption application, use the following command:
   ```bash
     ./encryptify --encrypt <input_file> <output_file>
  
3. To decrypt a file, use:
   ```bash
    ./encryptify --encrypt <input_file> <output_file>
  

## Code Structure
encryptify/ <br>
├── .idea/               // IDE configuration files <br> 
├── .vscode/             // Visual Studio Code configuration files <br>
├── src/                 // Source files <br>
│   └──> main.cpp        // Main application logic <br>
│   └──> app/             //Application specific logic <br>
├── .env                 // Environment variables configuration <br>
├── .gitignore           # Files to ignore in Git <br>
├── Makefile             # Build instructions <br>
└── makeDirs.py          # Script to create necessary directories <br>

## Usage
1. Start by compiling the application as mentioned above.
2. Use the command-line interface to encrypt or decrypt files.
3. Ensure that the files you are working with have the appropriate permissions for reading and writing.

## Contributing
Contributions are encouraged! Please follow these steps to contribute:

I. Fork the repository: git checkout -b feature/YourFeature
II.Make your changes and commit: git commit -m "Add your feature"
III. Push to the branch: git push origin feature/YourFeature
IV. Create a pull request.

## Acknowledgments
Inspired by the need for secure file handling and modern encryption techniques. Special thanks to the open-source community for their contributions and shared knowledge in C++ development.


## Developer
This project is developed by ***Shobhit Singh***

Feel free to reach out for any questions or collaborations!
