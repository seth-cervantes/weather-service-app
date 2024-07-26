# Weather Server

This is a simple HTTP server written in Go that uses the OpenWeather API to get current weather data based on latitude and longitude coordinates.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Endpoints](#endpoints)
- [Environment Variables](#environment-variables)
- [License](#license)

## Installation

To install and run this project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/seth-cervantes/weather-service-app.git
   cd weather-server
   ```

2. **Install dependencies:**

   The project has no external dependencies besides the `godotenv` package. Install it by running:

   ```bash
   go get github.com/joho/godotenv
   ```

3. **Set up environment variables:**

   Create a `.env` file in the root directory of the project and add your OpenWeather API key:

   ```ini
   OPENWEATHER_API_KEY=your_api_key_here
   ```

## Usage

To run the server, use the following command:

```bash
go run main.go
```
