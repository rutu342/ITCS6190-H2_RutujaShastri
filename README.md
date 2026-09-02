# ITCS6190-H2_RutujaShastri
Name : Rutuja Hemant Shastri
Student ID : 801484366
Email : rshastri@charlotte.edu

# ITCS 6190/8190 – Hands-On L3
## Building a Multi-Container Python Web Application with Docker Compose

### Overview

This hands-on demonstrates how to build and run a simple Python Flask web
application using Docker and Docker Compose. The application uses Redis as
a separate container to maintain a page-visit counter.

The application consists of two services:

- **Flask Web Application** – Handles HTTP requests and displays the visit count.
- **Redis** – Stores and increments the number of page visits.

Docker Compose is used to build, connect, and run both services together.

## Project Structure

```text
ITCS6190-H2_RutujaShastri/
│
├── app.py
├── Dockerfile
├── compose.yaml
├── requirements.txt
├── README.md
├── .gitignore
└── screenshots/
## Steps to Execute the Project

### 1. Clone the Repository

Clone the GitHub repository using:

```bash
git clone https://github.com/rutu342/ITCS6190-H2_RutujaShastri.git
cd ITCS6190-H2_RutujaShastri
###Verify Project Files
app.py
Dockerfile
compose.yaml
requirements.txt
README.md
.gitignore
docker compose up
###Open the Web Application
http://localhost:8000

