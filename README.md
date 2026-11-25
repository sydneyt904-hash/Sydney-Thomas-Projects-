# Sydney Thomas — Academic Project Portfolio

A collection of two university software projects, organized in one repository. Each project has its own folder and documentation.

## Projects

### 1. Software Engineering — CS 372 Final Project
**Folder:** [Software-Engineering](./Software-Engineering/)

A Java web application created for a Software Engineering course. The submitted source includes Java servlets and data-access classes, JSP pages, authentication and access-control flows, MySQL schema and seed scripts, and interface screenshots/diagrams.

**Technology:** Java, JSP, Servlets, MySQL, JDBC/MySQL Connector, Apache Tomcat, Eclipse, HTML, CSS, and JavaScript.

**Areas represented:** account creation and login, account activation/approval, access-control workflows, password recovery, content entry/modification, and database setup.

### 2. Programming for the Web — Final Project
**Folder:** [Programming-for-the-Web](./Programming-for-the-Web/)

A PHP web application created for a Programming for the Web course. The submitted source includes student and employee workflows, course and schedule pages, registration-related pages, shared PHP libraries, stylesheets, JavaScript, and a MySQL schema.

**Technology:** PHP, HTML, CSS, JavaScript, PDO, and MySQL/XAMPP.

## Repository layout

- `Software-Engineering/` — Java/JSP application, SQL scripts, project documentation, screenshots, and diagrams.
- `Programming-for-the-Web/` — PHP pages/libraries, JavaScript, stylesheets, images, and database schema.

## Setup notes

These are academic project source files, not turnkey hosted services. Each application needs its local runtime and database configured. The Software Engineering project needs a Java servlet/JSP container such as Tomcat and MySQL. The Programming for the Web project needs PHP with PDO MySQL support and a local MySQL/MariaDB server such as XAMPP.

Database passwords and local session state are not included. Use the `.env.example` files as local configuration references; never commit real credentials or real student/employee records.

## Academic context

These projects were created as coursework. The Software Engineering project was a group project; retain team attribution and publish only material that contributors and the course permit you to share publicly.
