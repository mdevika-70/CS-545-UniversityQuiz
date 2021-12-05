CS 545: Human Computer Interaction at Stevens Institute of Technology

## Group Members
1. Aditya Shivankar
2. Devendra Chauhan
3. Devika Mhatre
4. Neil Naidu
5. Sudarshana Sarma

## UniversityQuiz Application
This repository contains the source code for the UniversityQuiz application. This application acts as a university test/quiz application which aids university and/or professors to conduct online quiz/tests. Students can register and enroll themselves in their university and attempt the tests within a fixed time set by the professor. They can view the grades/scores from the dashboard. There will be multiple choice questions-based quiz for students, which students have to complete till the test date is due within the given time limit set for the test. The purpose of this application is to provide an eLearning examination website that will aid distance learning students and teachers to give online quizzes.

## Prerequisites
* npm: https://nodejs.org/en/
```sh
  npm install npm@latest -g
  ```
* Seed file
```sh
  node seed
  ```

## Application workflow
1. By default, the students are not enrolled in any categories, which means they are inactive. They need to be verified by the professor.
2. Student needs to login and click on "enroll" button to enroll themselves in any course/category. 
3. Once clicked on enroll, professor will receive the request for the verification. Only one time verification per student per university is needed. Student can enroll without verification for courses from the same university after the initial verification.
4. Student needs to relogin to access the student portal and the quizzes because the session needs to be reinitiated.

## How to install?
1. clone the repository
```sh
   git clone https://github.com/mdevika-70/CS-545-UniversityQuiz.git
   ```
2. Install the npm packages
```sh
   npm install
   ```
4. Run the application
```sh
   npm start
   ```
5. The result will be available at http://localhost:3000
