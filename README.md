# CNCjs & MJPG-Streamer with Docker Compose

This repository provides a straightforward setup for [CNCjs](https://cnc.js.org/) (a web-based CNC controller software) and [MJPG-Streamer](https://mjpg-streamer.sourceforge.net/) (for live video streaming from a webcam) using [Docker Compose](https://docs.docker.com/compose/).

![screenshot](https://raw.githubusercontent.com/YuseiIto/cncjs-docker-compose/main/screenshot.png)

## Overview

This project offers a containerized environment to control your CNC machine while simultaneously streaming live video from a webcam. This allows for quick deployment of CNCjs and MJPG-Streamer without worrying about dependency conflicts on your host system.

## Features

* **Easy Setup**: Launch both CNCjs and MJPG-Streamer simultaneously with a single `docker-compose.yml` file.
* **Isolated Environment**: Run the software in a clean, isolated environment without direct installation on your host machine.
* **Webcam Support**: Easily integrate live streaming of your CNC work via MJPG-Streamer.

## Prerequisites

* Docker
* Docker Compose

## Usage

1.  **Clone the Repository**:

```bash
git clone [https://github.com/YuseiIto/cncjs-docker-compose.git](https://github.com/YuseiIto/cncjs-docker-compose.git)
cd cncjs-docker-compose
```

2. **Launch the Services**:

```bash
docker-compose up -d
```
