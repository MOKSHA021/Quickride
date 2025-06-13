# 🚖 Quick Ride – Nearby Cab Finder

## 📝 Overview

**Quick Ride** is a C++ based simulation project that allows users to find the nearest cab based on their current geographic coordinates. It uses the **Great Circle Distance** formula to compute the shortest distance between two points on the surface of a sphere (like Earth), offering a precise and efficient way to determine the closest cab.

This project demonstrates real-world application scenarios using C++ programming, GPS data simulation, and optional integration with technologies like databases, payment APIs, and cloud deployment.

---

## 🌟 Features

- 📍 Accepts real-time **user geolocation** input (latitude, longitude).
- 🚕 Stores a list of available cabs with GPS coordinates.
- 🧭 Calculates distance using the **Great Circle Distance Formula**.
- 📊 Sorts cabs by distance and returns the **nearest cab**.
- 🗺️ Optionally integrates with **Google Maps API** to visualize routes.
- 💳 Demonstrates cab fare estimation and mock **payment gateway** integration.
- ☁️ Designed for **cloud deployment** and scalability.

---

## 📐 Great Circle Distance Formula

\[
d = R \cdot \arccos\left(\sin(\phi_1) \cdot \sin(\phi_2) + \cos(\phi_1) \cdot \cos(\phi_2) \cdot \cos(\lambda_2 - \lambda_1)\right)
\]

Where:
- \( R \) is Earth's radius (6371 km)
- \( \phi_1, \phi_2 \): latitudes (in radians)
- \( \lambda_1, \lambda_2 \): longitudes (in radians)

This formula calculates the shortest path between two locations on Earth’s surface.

---

## 💻 Technologies Used

| Purpose                    | Technology                     |
|----------------------------|--------------------------------|
| Core Programming           | C++17                          |
| Distance Calculation       | Great Circle Distance Formula  |
| Cab Data Storage           | `cabs.csv` / MySQL / SQLite    |
| Geolocation Mapping (opt.) | Google Maps API / Leaflet.js   |
| Payments (mock)            | Stripe / Razorpay Sandbox      |
| Deployment (optional)      | Docker, AWS EC2 / GCP / Heroku |

---

## 🗂️ Folder Structure

