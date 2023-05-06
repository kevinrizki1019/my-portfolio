# My Portfolio Website using Laravel 9

This repository contains the source code for my personal portfolio website, built using Laravel 9.

## Overview

My portfolio website is a showcase of my skills, projects, and experiences. It includes information about my education, work history, and technical skills, as well as a portfolio of my projects and a blog where I share my thoughts and insights.

The website is built using Laravel 9, a popular PHP web framework that provides powerful tools for building scalable and secure web applications. It uses a modern front-end stack including Tailwind CSS and Alpine.js, and is fully responsive and optimized for performance.

## Features

The portfolio website includes the following features:

- Home page with an overview of my skills and projects
- About page with information about my education and work history
- Portfolio page with examples of my projects and their descriptions
- Blog page with my latest articles and thoughts
- Contact page with a form to get in touch with me
- Admin dashboard for managing the content of the website

## Installation

To install and run the portfolio website using Docker Compose, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/my-portfolio-website.git`
2. Copy the `.env.example` file to `.env` and configure your environment variables
3. Run `docker-compose up -d` to start the containers
4. Run `docker-compose exec app php artisan key:generate` to generate an application key
5. Run `docker-compose exec app php artisan migrate` to run the database migrations
6. Visit `http://localhost:8000` in your browser to view the website

To stop the containers, run `docker-compose down`.

## Contributing

If you find any bugs or issues with the portfolio website, feel free to open an issue or submit a pull request. I appreciate your contributions!

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
