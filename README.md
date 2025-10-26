# Django REST Weather API

A backend service built with Django and Django REST Framework (DRF) designed to expose weather data via a clean, RESTful API endpoint.

This application connects to an external weather service (e.g., OpenWeatherMap) to retrieve current conditions and forecasts, making the data easily accessible for any front-end application.

## ✨ Features

* **RESTful Endpoint:** Provides weather data through a simple, standardized URL endpoint (e.g., `/api/weather/?city=London`).
* **External API Integration:** Handles requests to a third-party weather API.
* **Configuration Security:** Uses environment variables to securely manage API keys.
* **Django Admin:** Includes full Django administrative interface for management.

## ⚙️ Prerequisites

Before running this project, you need to have the following installed:

* Python (3.8+)
* pip (Python package installer)
