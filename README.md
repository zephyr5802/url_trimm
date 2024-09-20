# Full Stack URL Shortener with React JS, Tailwind CSS, Supabase, Shadcn UI

## Project Overview

Welcome to the Full Stack URL Shortener project! This project, created by Aditya, is a URL shortener application built using React JS for the frontend, Tailwind CSS for styling, Supabase for the backend, and Shadcn UI for the user interface components. The project is designed to help you shorten long URLs, track their usage, and manage them efficiently.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Shorten long URLs with ease
- Track the number of clicks for each shortened URL
- Simple and responsive user interface
- User authentication and URL management with Supabase
- Beautiful and customizable UI with Tailwind CSS and Shadcn UI

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

- Node.js and npm installed on your machine
- Supabase account for backend services

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/zephyr5802/url_trimm.git
   cd url_trimm
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Set up Supabase:

   - Create a new project in Supabase.
   - Note down the Supabase URL and API key.
   - Set up the database schema as shown in the project documentation.

4. Configure environment variables:

   Create a `.env` file in the root directory and add the following variables:

   ```plaintext
   REACT_APP_SUPABASE_URL=your_supabase_url
   REACT_APP_SUPABASE_KEY=your_supabase_key
   ```

### Running the Application

1. Start the development server:

   ```bash
   npm start
   ```

2. Open your browser and navigate to `http://localhost:3000`.

## Usage

1. Register or log in to the application.
2. Enter a long URL that you want to shorten.
3. Click the "Shorten" button to generate a short URL.
4. Use the shortened URL and track its click count in the dashboard.

## Contributing

We welcome contributions to make this project even better! To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature/YourFeature
   ```

3. Make your changes and commit them:

   ```bash
   git commit -m 'Add some feature'
   ```

4. Push to the branch:

   ```bash
   git push origin feature/YourFeature
   ```

5. Open a pull request.


---

Feel free to reach out if you have any questions or need further assistance. Happy coding! 🚀
