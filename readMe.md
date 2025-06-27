# Treasury Movement Simulator

Welcome to the **Treasury Movement Simulator**, a web-based tool designed to manage and simulate fund transfers across 10 virtual accounts in three currencies: KES, USD, and NGN. This project was initiated by a user and brought to life with the assistance of **Grok 3**, an AI developed by xAI, which generated the code, provided design suggestions, and ensured functionality based on the outlined requirements.

## Overview

The Treasury Movement Simulator allows treasury teams to:
- View balances across 10 virtual accounts with unique names and currencies.
- Transfer funds between accounts, with validation for sufficient balance.
- Log all transactions in a filterable table.
- Optionally simulate FX conversions and future-dated transfers (UI-only).

This tool was created as part of a challenge to build a mini financial management interface, with bonus features implemented to enhance its utility.

## Features

- **Account Management**: Displays 10 accounts (e.g., Mpesa_KES_1, Bank_USD_3) with balances in KES, USD, or NGN.
- **Fund Transfers**: Move money between accounts with amount and optional notes; validates source balance.
- **Transaction Logging**: Records all transfers with timestamps, source, destination, amount, and notes.
- **Bonus Features**:
  - FX conversion support with static rates (e.g., 1 USD = 130 KES, 1 USD = 1000 NGN).
  - Filter logs by account or currency.
  - Simulate future-dated transfers (displayed but not executed until the scheduled time).

## Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Edge).
- Internet connection (to load Tailwind CSS and Font Awesome CDNs).

No additional software or server setup is required, as this is a static HTML/JavaScript application.

## Installation

1. Clone or download this repository to your local machine:
   ```bash
   git clone <repository-url>