# API Documentation

## Authentication

All API requests require OAuth 2.0.

## Endpoints

- `/cards`: Manage virtual cards  
- `/transactions`: Transaction history  
- `/balance`: Check balance

## Example Request

```bash
curl -X GET "https://api.vextapay.com/cards" -H "Authorization: Bearer TOKEN"
