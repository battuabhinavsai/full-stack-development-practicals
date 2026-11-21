# Deployment Guide

This repository contains independent learning projects. The root `render.yaml` defines 11 static React sites and 7 Node.js web services so each project gets its own URL. The MERN project has separate frontend and backend services.

## Before deploying

1. Push `render.yaml` and any later changes to the `main` branch on GitHub.
2. Create a MongoDB Atlas Free cluster for the six MongoDB-backed apps. Use one database user and separate database names for each practical. Do not put the Atlas password in a source file or commit it to GitHub.
3. In Atlas, add the Render service egress IP ranges to the Atlas IP access list. Avoid allowing `0.0.0.0/0` unless you understand the exposure it creates.
4. In Render, create a Blueprint from this repository and review the services and environment variables before confirming. Render will ask for the MongoDB connection strings; enter them in the dashboard prompt only.
5. After the services are created, verify the MERN API URL. If Render assigned a different URL than the one in `VITE_API_BASE_URL`, update that environment variable on the MERN frontend service and redeploy it.
6. After each service is live, add its URL to the project list in the root README.

## Included services

- **11 static sites:** the 10 standalone React practicals and the MERN frontend.
- **7 Node services:** books API, Mongoose movies API, authentication API, MVC movies API, file-persistence API, EJS products app, and MERN API.
- **6 MongoDB-backed services:** use Atlas connection strings supplied through Render environment variables. The products file API uses a local JSON file instead.

## Free-tier behavior

Render Free web services sleep after 15 minutes without requests and can take about a minute to wake. The free web services share a monthly instance-hour allowance. The file-persistence practical writes to local disk, so its changes can disappear when a free service sleeps, restarts, or redeploys. These deployments are for learning and demos.

## React Router

The React Router and MERN frontend sites include a rewrite to `index.html` so direct visits to nested browser routes reach the React app.