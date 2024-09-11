# Exchange Rate API

A Python-based RESTful API that fetches and provides real-time exchange rate information using Flask and SQLite. This API can be used for financial applications, sales quotation systems, or any service that requires current exchange rate data.

## Features

- Fetch real-time exchange rates from reliable sources.
- Supports multiple currency conversions.
- Stores exchange rate data in an SQLite database.
- Provides an API endpoint to retrieve historical and current exchange rate data.
- Automated data fetching and error handling using APScheduler.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

Ensure you have the following software installed on your computer:

- Python 3.7+
- Git
- Virtualenv

### Installation

1. **Clone the Repository:**

   ```bash
   git clone git@github.com:nace-martin/exchange_rate_api.git
   cd exchange_rate_api
