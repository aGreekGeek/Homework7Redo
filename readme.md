# QR Code Generator with Docker and Python

## Project Description

This project demonstrates how to use Docker with Python to create a program that generates a QR code containing a URL. The QR code can be scanned using a phone's camera to open the target website. For this assignment, the QR code redirects users to my GitHub homepage: [https://github.com/aGreekGeek](https://github.com/aGreekGeek).

## Requirements

- **Python**: The program uses Python and the `qrcode` library to generate QR codes.
- **Docker**: The application is containerized using Docker for easy deployment and execution.

## Features

- Generates a QR code PNG file for a given URL.
- Saves the generated QR code locally using Docker's volume mapping feature.
- Completely portable and runs in a lightweight Docker container.

## Installation and Usage

### Prerequisites

1. Install [Docker](https://www.docker.com/get-started) on your system.
2. Clone or download this repository.

### Building the Docker Imageory and build the Docker image:

```bash
docker build -t my_qrcode .