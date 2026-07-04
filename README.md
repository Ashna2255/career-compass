# Career Compass

A responsive career guidance web application that helps students discover a career field suited to their interests through an interactive aptitude test.

## Overview

Career Compass presents students with a series of multiple-choice questions spanning various career fields. Each question offers a minimum of four options, and every option is mapped to a specific field with an associated point value. As the student answers, their option-wise scores are aggregated across all questions, and the platform recommends the field with the highest cumulative score — giving students a data-driven starting point for exploring career paths.

## Features

- **Interactive aptitude test** — multiple-choice questions covering a range of career fields
- **Field-weighted scoring system** — every answer option contributes points toward a specific field
- **Automatic field recommendation** — results are calculated from the student's cumulative scores
- **Structured navigation** — clean, user-friendly interface for browsing and completing the test
- **Responsive design** — works across desktop and mobile screens

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express
- **Database:** MongoDB

## Getting Started

### Prerequisites

- Node.js (v16 or later recommended)
- MongoDB (local instance or a hosted cluster, e.g., MongoDB Atlas)

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/Ashna2255/career-compass.git
   cd career-compass
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Configure environment variables
   Copy `.env.example` to `.env` and fill in your own values:
   ```bash
   cp .env.example .env
   ```

4. Start the server
   ```bash
   npm start
   ```

5. Open the app in your browser at `http://localhost:5000` (or the port set in `.env`)

## How the Scoring Works

Each question in the test presents multiple options, and each option is pre-mapped to a specific career field along with a point value. As a student completes the test, their selections are tallied per field. Once all questions are answered, the field with the highest total score is presented as the recommended career path.

## Project Structure

```
career-compass/
├── models/       # MongoDB schemas
├── routes/       # Express route handlers
├── public/       # Frontend static assets (HTML, CSS, JS)
├── server.js     # App entry point
├── .env.example  # Sample environment variables
└── package.json
```

## License

This project is for educational purposes as part of a personal/academic portfolio.
