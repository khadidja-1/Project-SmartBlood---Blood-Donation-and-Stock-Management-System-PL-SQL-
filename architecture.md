

 General Architecture

The Smartblood system is composed of:

Mobile App (Donor App) — Flutter / React Native

Admin Dashboard — Web (Laravel / Node.js / React)

Backend API — REST API built with PHP/Laravel or Node.js

Database — Oracle 21c

Internal Services — Verification, compatibility, availability

 Communication

The mobile app communicates with the API through HTTPS.

The API communicates with Oracle using an official driver.

The admin dashboard interacts with internal API endpoints.

Hospitals access services through a secure portal.
