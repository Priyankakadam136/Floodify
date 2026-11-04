# Floodify – Real-Time Flood Monitoring & Safety Platform

## Project Overview

Floodify is a flood monitoring and safety platform designed to help users monitor flood-affected areas, report incidents, and locate nearby shelters and hospitals.

## Tech Stack

**Frontend:** React.js, JavaScript, HTML5, CSS3, Axios, React Router

**Backend:** Java, Spring Boot, Maven

**Database:** MySQL, Amazon RDS

**Cloud:** AWS EC2, AWS VPC, AWS RDS

**Tools:** Git, GitHub, Docker, Jenkins

## Architecture

React Frontend → Spring Boot Backend (AWS EC2) → MySQL Database (Amazon RDS)

## Project Features

- Flood monitoring dashboard
- Flood-prone area visualization
- Emergency alerts
- Shelter and hospital information
- Incident reporting

## Deployment Documentation

The AWS deployment guide is available here:

[EC2 and RDS Deployment Guide](docs/deployment/Floodify-AWS-EC2-RDS-Deployment.pdf)

The guide covers:
- VPC and networking configuration
- EC2 instance setup
- Amazon RDS configuration
- Backend deployment
- React frontend deployment
- Database connectivity

## Running Locally

### Frontend

```bash
npm install
npm start
```

### Backend

```bash
cd floodify_backend
mvn clean install
```

Run the generated Spring Boot JAR using the appropriate configuration.

## Repository Structure

- `src/` – React frontend
- `public/` – Static frontend assets
- `floodify_backend/` – Spring Boot backend
- `docs/` – Project and deployment documentation

## Author

Priyanka Kadam