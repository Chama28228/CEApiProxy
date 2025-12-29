# CO528 Lab 01 – ESB using WSO2 Micro Integrator (WSO2 MI)

This repository contains my **Lab 01** implementation for building an **ESB-based Research Group API** using **WSO2 Micro Integrator (MI)**.

## Overview
The integration exposes a proxy API layer and internally calls backend department services (e.g., publications / research-group related services).  
It also uses **Data Mapper** to transform backend responses into the required output format.

## What’s Included
- WSO2 MI Integration Project (API + Endpoints + Mediation flows)
- Data Mapper configurations for response transformation
- Logging mediators for verification/debugging

## Technologies
- WSO2 Micro Integrator (MI)
- WSO2 Integration Studio / VS Code MI Extension
- HTTP Endpoints, Call Mediator, Log Mediator, Respond Mediator
- Data Mapper (Payload Transformation)

## How to Run (Local)
1. Open the project in **VS Code** with the **WSO2 Integrator: MI** extension installed.
2. Make sure the MI runtime is configured (auto-download or local runtime).
3. Click **Build and Run** from the MI extension.
4. MI will start locally (default gateway is usually on port **8290**).

## Testing
Send requests to the exposed API resources (examples depend on your implementation), and check:
- API response in Postman/curl/browser
- MI console logs for flow execution

## Notes
- This project demonstrates how an ESB can act as a single integration layer for department services by routing and transforming responses.

## Author
- Name: Chamath Rupasinghe
- Index No: E/20/342
- Course: CO528
