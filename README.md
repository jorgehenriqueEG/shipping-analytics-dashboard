# Shipping Analytics Dashboard

A simple web dashboard for visualizing shipping data by carrier using dynamic charts.

This project demonstrates how to build a lightweight analytics interface using HTML, JavaScript, and Chart.js to display shipment data in multiple chart formats.

## Features

- Dynamic charts using Chart.js
- Date filtering
- Switch between chart types:
  - Bar
  - Pie
  - Line
- Shipment visualization by carrier
- Lightweight and fast (no framework required)
## Technologies Used

- HTML5
- JavaScript (Vanilla JS)
- Chart.js

## Project Structure


dashboard.html


## How It Works

The dashboard loads shipping data and allows the user to:

1. Select the chart type
2. Filter shipments by date
3. Visualize shipments grouped by carrier

Currently the data is simulated locally inside the JavaScript code, but it can easily be integrated with:

- REST APIs
- JSON endpoints
- Google Sheets
- CSV exports
- Database connections

## Example Data Format


{
"data": "2026-01-27",
"transportadora": "Correios",
"quantidade": 50
}


## Future Improvements

- API integration for real-time data
- Dashboard styling improvements
- Multiple dataset comparison
- Export reports
- Authentication and user access

## Author

Jorge Henrique de Araujo Vitorino  
Computer Engineering Student
