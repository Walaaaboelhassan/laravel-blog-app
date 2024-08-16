# Blog App

## Overview

The Blog App is a modern blogging platform that allows users to create, update, delete, and manage blog posts. The application uses Laravel for the backend and features a responsive frontend built with Tailwind CSS and Alpine.js. It uses a MySQL database for storing user and post data.

## Features

- **User Authentication**: Register, log in, and manage user sessions.
- **CRUD Operations**: Create, read, update, and delete blog posts.
- **Responsive Design**: Styled with Tailwind CSS for a modern, responsive look.
- **Interactive UI**: Enhanced with Alpine.js for dynamic frontend interactions.

## Technologies

- **Backend**: Laravel (PHP framework)
- **Frontend**: Tailwind CSS, Alpine.js
- **Database**: MySQL
- **Build Tool**: Laravel Mix

## Installation

### Prerequisites

- PHP >= 7.3
- Composer
- Node.js >= 14.x
- npm or yarn
- MySQL

### Setup

1. **Clone the Repository**

    ```bash
    git clone https://github.com/yourusername/blog-app.git
    cd blog-app
    ```

2. **Environment Configuration**

    Copy the `.env.example` file to `.env`:

    ```bash
    cp .env.example .env
    ```

    Generate a new application key:

    ```bash
    php artisan key:generate
    ```

3. **Install Dependencies**

    Install PHP dependencies:

    ```bash
    composer install
    ```

    Install Node.js dependencies:

    ```bash
    npm install
    ```

4. **Database Setup**

    Create a new MySQL database and update your `.env` file with the database credentials.

    Run the database migrations:

    ```bash
    php artisan migrate
    ```

    Optionally, seed the database with initial data:

    ```bash
    php artisan db:seed
    ```

5. **Compile Frontend Assets**

    Compile assets for development:

    ```bash
    npm run dev
    ```

    For production builds, use:

    ```bash
    npm run prod
    ```

## Running the Application

Start the Laravel development server:

```bash
php artisan serve

thank you
walaa zidan