# Dream Airways – Airline Ticketing System

A Python and MySQL command-line project that simulates a basic airline ticketing system. It allows users to book tickets, calculate bills based on selected services, check ticket status, and cancel bookings, with data stored and managed using a MySQL database.

## Features

- Ticket Booking: Collects passenger details and generates a unique PNR  
- Billing: Calculates charges based on travel class, luggage selection, and optional in-flight menu items  
- Ticket Status Check: Allows users to check ticket status using PNR, email ID, or phone number  
- Cancellation: Updates ticket status to "Cancelled" upon user request  
- Database Initialization: Automatically sets up required tables (if not already created) on first run

## Tech Stack

- Programming Language: Python  
- Database: MySQL  
- Libraries Used: `pymysql`, `random`

## Setup Instructions

### Prerequisites

- Python 3.x installed  
- MySQL installed and running locally  
- `pymysql` library installed (`pip install pymysql`)

### Installation & Usage

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/airline-ticketing-system.git
   cd airline-ticketing-system
