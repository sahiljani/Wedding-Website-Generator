
# Wedding Website Generator

![Wedding Website Generator](https://i.imgur.com/JEnk1bD.png)

A comprehensive **Laravel** application designed to help users create a personalized wedding website. This platform provides complete event management, including an **Add to Calendar** feature, location details, and theme customization. With **Tailwind CSS** for styling and **AJAX** for seamless interactivity, this project enables users to showcase their wedding details in a modern, elegant format.

## Key Features

- **Dynamic Event Management**: Add, update, and delete wedding events with date and time fields. The Add to Calendar feature allows guests to save events to their personal calendars.
- **Location Information**: Add multiple event locations with Google Maps integration for easy navigation.
- **Bride and Groom Profiles**: Customize profiles with photos, names, and family details.
- **Image Gallery**: Create an online gallery to display wedding photos, share memories, and build excitement.
- **Customizable Themes**: Select from different themes and preview them instantly, with Tailwind CSS for easy style customization.
- **Countdown Timer**: Display a live countdown to the main event, adding a dynamic touch to the site.
- **Additional Details**: Add custom messages or event descriptions for guests.

## Technology Stack

- **Laravel**: For backend management, database handling, and API routing.
- **Tailwind CSS**: Utility-first CSS framework for responsive, clean design.
- **AJAX**: Powers asynchronous requests for a seamless experience.
- **MySQL**: Database for persistent storage.

## Prerequisites

- **PHP** >= 8.0
- **Composer**
- **Node.js** and **NPM**
- **MySQL** (or compatible database)

## Installation and Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/sahiljani/Wedding-Website-Generator.git
   cd Wedding-Website-Generator
   ```

2. **Install PHP Dependencies:**
   ```bash
   composer install
   ```

3. **Install Node.js Dependencies** (for Tailwind CSS and other frontend assets):
   ```bash
   npm install
   ```

4. **Environment Configuration:**
   - Duplicate `.env.example` and rename it to `.env`.
   - Configure the database and other settings in `.env`.
   - Generate an application key:
     ```bash
     php artisan key:generate
     ```

5. **Database Setup:**
   - Run migrations to create the necessary tables:
     ```bash
     php artisan migrate
     ```

6. **Compile Frontend Assets:**
   - For development:
     ```bash
     npm run dev
     ```
   - For production:
     ```bash
     npm run production
     ```

7. **Run the Development Server:**
   ```bash
   php artisan serve
   ```
   The application will be accessible at `http://localhost:8000`.

