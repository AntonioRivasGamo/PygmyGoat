# PygmyGoat 🐐
> **A lightweight, high-performance cluster monitoring system built with Go, Python (FastAPI), and TypeScript (React).**

---

## Project Overview

This project currently serves as a **learning laboratory** designed to build a modern distributed systems architecture from scratch. 
The primary goal is to master full-stack and backend software development using industry-standard technologies:

* **Go:** Low-level system interaction, lightweight agents, and concurrent metric collection.
* **Python (FastAPI):** High-performance RESTful APIs, asynchronous processing, and strict schema validation with Pydantic.
* **React + TypeScript:** Type-safe, component-driven, and interactive web dashboards.

---

## System Architecture & Tech Stack

* **Agent (Slave):** Written in **Go** and containerized in an **Alpine Linux** image.
* **Backend (Master):** Built with **Python (FastAPI)**, utilizing asynchronous execution and Pydantic validation.
* **Database:** **PostgreSQL** for relational persistence, with an architectural path to adopt **TimescaleDB** for scalable time-series data handling.
* **Frontend (Client):** Developed in **React** with **TypeScript** for real-time visualization and interactive dashboards.

---

## Module Status

| Module | Component | Tech Stack | Status | Description |
| :--- | :--- | :--- | :--- | :--- |
| **Agent** | *Slave* | Go, Alpine | Planning | System metric collector and HTTP transport. |
| **Backend** | *Master* | Python, FastAPI, PostgreSQL | Planned | REST API for metric ingestion, validation, and storage. |
| **Dashboard** | *Client* | React, TypeScript | Planning | Interactive frontend for real-time data visualization. |

---

## License

This project is licensed under the **GNU General Public License v3.0 (GPL-3.0)**. 
