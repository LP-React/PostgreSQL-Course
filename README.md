# PostgreSQL - Things learned
<p align='center'>
  <img src="https://miro.medium.com/v2/resize:fit:610/1*mMq3Bem9r8ASAn1YwcTbEw.png" width="450px">
</p>

Here are the things I have learned, you can use this as a roadmap if you want to learn from basic SQL up to advanced SQL with [PostgreeSQL](https://www.postgresql.org). 

We will be working with TablePlus or PHPMyAdmin, and we will also need to have **Docker** installed on our system. If you have never worked with Docker before, don't worry, it's simple.

## Required Installations

  - [Docker](https://www.docker.com)
  - [TablePlus](https://tableplus.com)

## Prepare the enviorement

  1. Download the [docker-compose.yml](docker-compose.yml) file.
  2. Create a folder and move the **docker-compose.yml** file there.
  3. Open the terminal and run.

      ```
      docker pull postgres:15.3
      docker pull dpage/pgadmin4
      ```

  4. Now navigate to the created folder and run `docker compose up -d`.
  5. Close the terminal, open TablePlus, and add a new connection. Fill in the fields with the following information:
      ```
      Name: learning-sql 
      Host: localhost
      Port: 5432
      User: student
      Password: 123456
      Database: course-db
      ```
      Then, click on connect.

## Sections
1. ### Basics and First Steps 
    - [ ] Uploaded
2. ### Aggregate functions, Grouping and Ordering
    - [ ] Uploaded
3. ### Relations Key and Constraints
    - [ ] Uploaded
4. ### Data separation in other tables
    - [ ] Uploaded
5. ### Joins-Unions
    - [ ] Uploaded
6. ### Queries Dates, Intervals and Function
    - [ ] Uploaded
7. ### Generation of Primary Keys
    - [ ] Uploaded
8. ### Database Design
    - [ ] Uploaded
9. ### Database Exercises and Functions
    - [ ] Uploaded
10. ### Database Design II
    - [ ] Uploaded
11. ### Views, Materialized Views, and Common Table Expressions (CTE)
    - [ ] Uploaded
12. ### Custom Functions
    - [ ] Uploaded
13. ### Store_procedures
    - [ ] Uploaded
14. ### Triggers_Functions_and_Procedures
    - [ ] Uploaded

### 🔗 Connect with me
---
<p align="center">
<a href="https://github.com/LP-React"><img src="https://img.shields.io/badge/-Laysson-444346?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/laysson-polo/"><img src="https://img.shields.io/badge/-laysson%20polo-0077B5?style=for-the-badge&logo=Linkedin&logoColor=white"/></a>
<a href="mailto:ljamirp30@gmail.com"><img src="https://img.shields.io/badge/-ljamirp30@gmail.com-D14836?style=for-the-badge&logo=Gmail&logoColor=white"/></a>
<a href="https://www.instagram.com/lp.react/"><img src="https://img.shields.io/badge/-lp.react-E4405F?style=for-the-badge&logo=Instagram&logoColor=white"/></a>
<a href="https://www.discordapp.com/users/686343389985243289"><img src="https://img.shields.io/badge/-LP.React-7249fa?style=for-the-badge&logo=discord&logoColor=white"/></a>
</p>