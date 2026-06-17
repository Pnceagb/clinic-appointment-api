# Clinic Appointment API

This project is a simple Clinic Appointment API built using FastAPI and Docker.


## Laboratory Context
This project was developed in an offline Windows 11 laboratory environment.
Python was not installed directly on the computer. The application was executed using Docker and a prebuilt Docker image named clinic-fastapi-base:1.0.

## Features
- Create clinic appointments
- View all appointments
- View one appointment
- Update appointment details
- Cancel appointments

## Technologies Used
- Python
- FastAPІ
- Docker
- Git

## How to Run
docker compose up --build

Open http://localhost:8000/docs.

# Authentication

This API uses a Token-based authentication approach. To access protected resources, you must include a valid token in the Authorization header of your HTTP requests.

## Test Account
It provides a set of hardcoded, predictable credentials (usually a username/email and a password) that anyone testing the API can use immediately.

## Login Endpoint
The specific URL (route) responsible for authenticating a user and initiating their session.

## Protected Endpoints
Restricted routes within your application that require a user to prove who they are before granting access.

## Educational Limitations
Crucial note indicating that the security architecture of the project was built to teach or demonstrate a concept, not to withstand real-world attacks.