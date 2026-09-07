# Dance Battle

A robotics software project developed as part of a Computer Science engineering program.

## Overview

Dance Battle is a robotic application designed for a dance competition between robots.

The project combines a graphical user interface, robot control, and HTTP-based communication between the different components of the system.

The application allows users to connect to a robot, calibrate its colors, control its movements, manage dance sequences, and execute predefined choreographies.

## Features

- Graphical user interface built with PyQt6
- Robot connection and control
- Robot movement and arm control
- Color calibration
- Dance and choreography management
- Loading and execution of `.battle` files
- Score calculation based on predefined rules
- HTTP communication between the client application and the server
- Server-side management of robot-related operations

## Architecture

The project is divided into two main applications:

```text
app_joueur/
├── client/      # Client-side communication
├── dance/       # Dance and choreography management
├── robot/       # Robot-related logic
├── ui/          # Graphical user interface
└── main.py      # Application entry point

app_server/
├── server/      # Server and communication logic
├── UI/          # Server-side graphical interface
├── styles/      # Application styles
└── main.py      # Server entry point
```

The client application provides the main user interface and communicates with the server. The server handles the corresponding robot-related operations and communication.

## Technologies

- Python
- PyQt6
- HTTP
- Git
- GitHub
- Python virtual environment (`venv`)

## Project Structure

The main components of the project include:

- `app_joueur/client/` — client-server communication
- `app_joueur/dance/` — dance and choreography logic
- `app_joueur/robot/` — robot-related classes and operations
- `app_joueur/ui/` — graphical user interface
- `app_server/server/` — HTTP server and robot management
- `app_server/UI/` — server-side graphical interface
- `app_server/.battle` — scoring rules used during battles

## My Contribution

This project was developed in a three-person team.

I mainly worked on the graphical user interface using PyQt6 and on its integration with the robot control component.

My contributions included:

- Developing several graphical interfaces for robot connection, calibration, control, and dance management.
- Integrating user interface actions with robot movement functions in collaboration with the teammate responsible for the robot software.
- Contributing to the organization and structure of the application.
- Participating in project planning using Gantt scheduling.
- Contributing to collaborative development using GitHub.

## Team

The project was developed by a three-person team, with work divided mainly between:

- Graphical user interface
- Robot control
- Server and HTTP communication

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/dance-battle-robotics.git
cd dance-battle-robotics
```

Create a Python virtual environment:

```bash
python -m venv venv
```

Activate the virtual environment.

On macOS and Linux:

```bash
source venv/bin/activate
```

On Windows:

```bash
venv\Scripts\activate
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

The project consists of a client application and a server application.

Start the server:

```bash
python app_server/main.py
```

Start the client:

```bash
python app_joueur/main.py
```

The applications require the appropriate robot and network configuration to communicate with the robotic system.

## Academic Context

This project was developed as part of an engineering course in Computer Science, with a focus on software development and robotics.
