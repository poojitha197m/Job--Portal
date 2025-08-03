
# Job Portal Web Application

This is a full-stack Job Portal web application developed using Java and Spring Boot. It allows recruiters to post jobs and candidates to register, log in, and apply for jobs.

## Overview

The application provides separate modules for recruiters and job seekers, supports job listings, candidate applications, and includes login/logout functionality with a user-friendly interface.

## Technologies Used

- Java
- Spring Boot
- Thymeleaf (template engine)
- HTML/CSS
- MySQL (database)
- Spring Data JPA
- Spring Security

## Features

- User registration and login
- Recruiter dashboard for posting and managing jobs
- Job seeker dashboard for browsing and applying to jobs
- Admin features (optional, if implemented)
- Search functionality for jobs
- Secure authentication

## How to Run

1. Clone the repository

2. Set up the database:
   - Create a database named `job_portal_db`
   - Update your `application.properties` with your DB credentials

3. Run the application:
   ```
   ./mvnw spring-boot:run
   ```

4. Access the app in your browser:
   ```
   http://localhost:8080
   ```


## Author

Poojitha Matta

## License

This project is for educational and demo purposes. You may reuse or modify it with attribution.
