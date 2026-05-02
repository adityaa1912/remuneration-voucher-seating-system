# Remuneration Voucher & Exam Seating Management System

## Overview

A full-stack web application developed for automating remuneration voucher generation and exam seating management at A. C. Patil College of Engineering. The platform streamlines manual administrative workflows through dynamic calculations, intelligent seating allocation, collision prevention, and role-based access control.

## Features

### Remuneration Voucher Generator

* Generate, preview, and print remuneration vouchers for examiners and moderators
* Dynamic remuneration calculations with automated Travel Allowance (T.A.) scaling
* Minimum ₹100 remuneration floor enforcement
* Interactive printable voucher preview matching official formats
* Role-based admin controls for managing rates, categories, and examiner configurations

### Exam Seating Management

* Interactive floor-based room selection system
* Dynamic room capacity management
* Division-based student allocation support
* Collision prevention for overlapping exam schedules
* Automated seating allocation with constraint validation
* PDF export for seating arrangements with print-optimized formatting

### Allocation Logic

* 3-pass allocation algorithm with home-floor priority
* Cross-year pairing validation for internals
* Single-year restriction support for term-end examinations
* Sequential roll number generation division-wise

## Tech Stack

**Frontend:** React.js, Vite, Axios, React Router
**Backend:** Node.js, Express.js
**Database:** PostgreSQL
**Authentication:** JWT Authentication

## Screenshots

*Add project screenshots here*

## Installation

### Clone Repository

```bash id="h4l4v6"
git clone https://github.com/adityaa1912/remuneration-voucher-seating-system.git
```

### Install Dependencies

```bash id="4jwx5z"
npm install
cd client
npm install
```

### Configure Environment Variables

Create a `.env` file in the root directory:

```env id="sx6j4g"
PORT=5000
DB_USER=postgres
DB_PASSWORD=your_password
DB_HOST=localhost
DB_PORT=5432
DB_NAME=renum_db
JWT_SECRET=your_secret_key
```

### Run Application

```bash id="w25z9m"
npm run dev
```

## Contribution

This project was developed collaboratively as part of a team project. I contributed to application workflows, feature development, testing, and system implementation.

## Author

Aditya Mengawade
