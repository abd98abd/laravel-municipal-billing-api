# Laravel Municipal Billing API

A RESTful API built with Laravel 11 for managing municipal billing systems.

## Features
- Token-based authentication using Laravel Sanctum
- User billing management
- Admin access to all bills

## Tech Stack
- Laravel 11
- PHP 8+
- MySQL
- Laravel Sanctum

## Installation

1. Clone the repository
2. Install dependencies using Composer
3. Configure environment variables and run migrations


## API Endpoints

### Authentication
- POST /api/register
- POST /api/login
- POST /api/logout

### Bills
- GET /api/bills
- POST /api/bills
- POST /api/bills/{id}/pay

### Admin
- GET /api/admin/bills

## Project Purpose
This project was built as a backend portfolio application to demonstrate real-world Laravel API development.
