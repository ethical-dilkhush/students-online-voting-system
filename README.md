# Students Online Voting System

A lightweight, web-based voting application built with PHP and MySQL. It lets administrators create voting events, manage candidate options, and track ballot results while students or voters cast votes through a simple login flow.

## Features

- Role-based login for admins and voters
- Create and manage voting categories and options with images
- Default active voting selection
- Ballot submission with per-user tracking
- Vote sheet and results views
- Local image uploads for voting options

## Tech Stack

- **Backend:** PHP
- **Database:** MySQL
- **Frontend:** HTML, CSS, Bootstrap, jQuery, DataTables
- **Icons:** Font Awesome, RemixIcon, IcoFont

## Installation

1. Clone or download the repository.
2. Import `database/voting_db.sql` into your MySQL server.
3. Update `db_connect.php` with your database host, username, password, and database name.
4. Serve the project with a local or remote PHP environment, for example:

   ```bash
   php -S localhost:8000
   ```

5. Open the app in a browser and log in with an initial admin credential if seeded in the SQL dump.

## Usage

- Log in as an admin to manage categories, options, users, and settings.
- Select a default active voting from the admin panel.
- Voters log in, view active voting, and cast their ballot.
- Use the vote sheet and view vote pages to inspect submissions.

## Project Structure

- `index.php` - Main application shell with navigation and modals
- `login.php` - Login page
- `admin_class.php` - Backend action handlers
- `ajax.php` - AJAX API router
- `db_connect.php` - Database connection
- `database/voting_db.sql` - Schema seed
- `assets/` - Vendor dependencies, styles, and client assets

## License

This project is released as-is for educational use.
