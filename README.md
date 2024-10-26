
## MDLZ-Snack-Tracker

A web-based application which serve as an interactive space where consumers can track their snack purchases, provide feedback, and help MDLZ gather data-driven insights on consumer preferences. 

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Architecture](#architecture)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User & Admin Authentication**: Supports separate login and registration for users and admins.
- **Purchase History**: Automatically records users' snack purchase history.
- **Reviews and Ratings**: Allows users to review and rate the snacks they’ve purchased.
- **Admin Privileges for MDLZ**: Grants admin access to MDLZ for monitoring and managing the platform.
- **Insights Dashboard**: MDLZ has access to a dedicated dashboard for aggregated data analysis on consumer trends and preferences.
- **Analytics**: View insights on popular snacks, regional trends, and overall consumption data.

## Tech Stack

### Backend
- **Java**
- **Spring Boot** for RESTful API development
- **PostgreSQL** as the database
- **Docker** for containerization
- **AWS** for deployment

### Frontend
- **Angular** for the user interface
- **Chart.js** for data visualization in the insights dashboard
- **REST APIs** for communication between frontend and backend

## Architecture

The **Bite N Bliss** application follows a microservices-based architecture, with a RESTful API backend built in Spring Boot and an Angular-based frontend. The backend is containerized using Docker and deployed on AWS, while the frontend communicates with the backend via REST APIs.

![Architecture Diagram](path/to/architecture-diagram.png)

## Setup and Installation

### Prerequisites

- **Java 11** or above
- **Node.js** and **npm** for the Angular frontend
- **Docker**
- **PostgreSQL**
- **AWS Account** for deployment




