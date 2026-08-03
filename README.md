# Exam Portal

The Exam Portal, a Full Stack application built with Spring Boot and React JS, serves as a comprehensive solution for universities to manage online examinations for students. The system consists of three main modules: Admin, Teacher, and Student.

## Features

- **Administrator Module:**
  - Add and manage grades.
  - Add and manage courses within grades.
  - Register teachers for specific grades.
  - View all teachers and students.
  - Schedule exams.

- **Teacher Module:**
  - Register students in the assigned grade.
  - Schedule exams for courses.
  - View upcoming and previous exams.
  - View student results.

- **Student Module:**
  - Register for exams in their assigned grade.
  - View upcoming exams.
  - Take exams at scheduled times.
  - Receive exam results via email.
  - View exam results.

## Getting Started

Follow the steps below to set up and run the Exam Portal locally.

## Configuration

1. Copy the `application.properties.sample` file and rename it to `application.properties`.
2. Open `application.properties` and replace the placeholder values with your actual database details.

3. Copy the `docker-compose.yaml.sample` file and rename it to `docker-compose.yaml`.
4. Open `docker-compose.yaml` and replace the placeholder values with your actual database details.

### Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Running the Application

1. Clone the repository:

   git clone [https://github.com/vipul-tech/assessment-platform](https://github.com/vipul-tech/assessment-platform/tree/main)
   

2. Start the application using Docker Compose:

   docker-compose up
   

3. Access the application:
   - Spring Boot Backend: http://localhost:8080
   - React Frontend: http://localhost:3000

4. Stop the application:

   docker-compose down

## Screenshots

![Screenshot_1](images/1.loginPage.png)

![Screenshot_1](images/2.adminAddCourse.png)

![Screenshot_1](images/3.adminAllStudents.png)

![Screenshot_1](images/4.teacherAllCourses.png)

![Screenshot_1](images/5.teacherProfile.png)

![Screenshot_1](images/6.registerStudent.png)

![Screenshot_1](images/7.ongoingExam.png)

![Screenshot_1](images/8.examresults.png)

![Screenshot_1](images/9.studentProfile.png)

## Contributing

**Developed by [Vipul Kumar](https://github.com/vipul-tech)**
