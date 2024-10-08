## About

The Investment Management System is a web application designed for managing user accounts and investments. It allows users to create and manage accounts, make investments, withdraw funds, and track transactions. The application supports daily interest calculations for investments. Also you can buy/sell crypto currencies with funds from your accounts.

## Features

- **Account Management**: Create and update accounts with different currencies(EUR,USD,CNY...).
- **Fund Transfer**: Transfer funds between accounts.
- **Investment Management**: Invest money into accounts with automatic daily interest accrual.
- **Transaction History**: View detailed transaction history for each account.
- **Crypto**: Buy/Sell crypto and check

## Requirements

- **PHP**: 7.4 or higher
- **Laravel**: 8.x or higher
- **Database**: SQLite
- **API Keys**:
    - CoinMarketCap API Key
    - ExchangeRate API Key

## Installation

### Clone the Repository

```bash
git clone https://github.com/Janis203/bank.git
cd bank
composer install
Create an .env file
Update the .env file with your database configuration and API keys:{
DB_CONNECTION=sqlite
DB_DATABASE=/path/to/your/database.sqlite

COINMARKETCAP_API_KEY=your_coinmarketcap_api_key
EXCHANGERATE_API_KEY=your_exchangerate_api_key
}
php artisan migrate
php artisan serve
Your application will be available at http://localhost:8000.

