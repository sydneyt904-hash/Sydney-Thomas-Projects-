# Programming for the Web — Final Project

This folder contains the submitted source for the Programming for the Web course final project.

## Technology
PHP, HTML, CSS, JavaScript, MySQL/MariaDB, PDO, and XAMPP.

## Contents
- `html files/` — PHP page routes, shared libraries, and student/employee workflows
- `javascript/` — browser-side scripts
- `style_sheet/` — application stylesheets
- `server-files/` — database connection helper, supporting PHP utilities, and SQL schema
- `media and images/` — visual assets used by the project

## Local setup
1. Install XAMPP with PHP and MySQL/MariaDB.
2. Copy the project into the local web root.
3. Create the database using `server-files/xampp_schema.sql`.
4. Set `BARRY_DB_HOST`, `BARRY_DB_PORT`, `BARRY_DB_NAME`, `BARRY_DB_USER`, and `BARRY_DB_PASSWORD` for your local environment.
5. Open the application through the local Apache server.

Database settings are read from environment variables. Do not publish credentials, session files, or real student/employee records. Local session files and records.json are excluded from the public package.
