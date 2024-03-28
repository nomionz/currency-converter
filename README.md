# Real-Time Currency Converter

![Demo](https://private-user-images.githubusercontent.com/72413805/317721384-6a0eb746-6647-4632-8172-1be9c0a49562.gif?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTE2Mjg0ODcsIm5iZiI6MTcxMTYyODE4NywicGF0aCI6Ii83MjQxMzgwNS8zMTc3MjEzODQtNmEwZWI3NDYtNjY0Ny00NjMyLTgxNzItMWJlOWMwYTQ5NTYyLmdpZj9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAzMjglMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMzI4VDEyMTYyN1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWJlNTAyODUzMDVjYjdiODY0OWQ3YjJjMjYyN2FjM2NiM2Y2NzZlMTdjY2QzYWNkMzViOWQ2MzBhMjU0ODdlYjImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.1ie4kjsm8ukYqY0sHAFrets0vP227NjasDkTHySe0A4)

## Description

This is a real-time currency converter that uses the [European Central Bank exchange rates data](https://www.ecb.europa.eu/stats/policy_and_exchange_rates/euro_reference_exchange_rates/html/index.en.html) to convert between different currencies. The user can input the amount of money they want to convert and select the currency they want to convert from and to. The app will then display the converted amount in real-time.

## How to run

1. Clone the repository
2. Run the following command to start the server
```bash
go run .
```
3. Open your browser and go to `http://localhost`

## Technologies

- [HTMX](https://htmx.org/) latest CDN
- [Tailwind CSS](https://tailwindcss.com/) latest CDN
- [Golang](https://golang.org/) 1.22
- [GoFiber](https://gofiber.io/) v2