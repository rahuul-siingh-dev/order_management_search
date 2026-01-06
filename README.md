# Order Management & Search API

## Overview
A backend service built with FastAPI to manage orders and perform search operations.
Includes GST calculation, clean architecture, and scalable API design.

## Tech Stack
- Python
- FastAPI
- REST APIs

## Features
- Create and update orders
- List orders
- GST calculation
- Search orders by item and price
- Modular router and service architecture

## Project Structure
- routers/
- services/
- models/
- schemas/
- utils/

## How to Run
```bash
pip install -r requirements.txt
uvicorn main:app --reload
