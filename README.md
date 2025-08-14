# Country Quiz

A **Postgres-powered mini-project** built with **Node.js**, **Express**, and **EJS**, offering a dynamic quiz interface on countries with server-rendered pages and database-driven functionality.

---

##  Table of Contents

1. [About](#about)  
2. [Features](#features)  
3. [Screenshots](#screenshots)  
4. [Tech Stack](#tech-stack)  
5. [Prerequisites](#prerequisites)  
6. [Installation & Setup](#installation--setup)  
7. [Usage](#usage)  
8. [Project Structure](#project-structure)  
9. [Environment Variables](#environment-variables)  


---

##  About
`country_quiz` is a lightweight quiz application that retrieves and presents country-based questions using **PostgreSQL** for data persistence. It leverages **EJS** for server-side templating and **Express.js** for routing and API responses.

---

##  Features
- Display quiz questions related to countries dynamically  
- Submit and store answers in **PostgreSQL**  
- Server-rendered pages using **EJS** for all views  
- Structured folder organization for clarity and maintainability

---

##  Screenshots

Main Page-

<img width="1021" height="844" alt="image" src="https://github.com/user-attachments/assets/1ba2f739-6adc-4dc2-9a5f-9f13086ed4ec" />

Incorrect Submission Alert-
<img width="1021" height="303" alt="image" src="https://github.com/user-attachments/assets/28f7d6ce-6383-4fb3-a96a-c786af9b6e83" />

Restart Game Button-
<img width="1021" height="303" alt="image" src="https://github.com/user-attachments/assets/3e426348-6de5-405a-b100-ca75263a7ca1" />

---

##  Tech Stack
- **Server-side**: Node.js + Express  
- **Template Engine**: EJS  
- **Database**: PostgreSQL  
- **Package Management**: npm  

---

##  Prerequisites
- Node.js v14 or higher  
- npm (comes bundled with Node.js)  
- PostgreSQL installed and running

---

##  Installation & Setup

```bash
git clone https://github.com/mk00786/country_quiz.git
cd country_quiz
npm install

1. Configure Postgres:

Create a database (e.g., country_quiz_db)

Import capitals.csv inside your postgres DS

Update .env with your connection credentials

2. Create a .env in the root folder:
DB_USER=your_pg_user
DB_PASSWORD=your_pg_password
DB_HOST=localhost
DB_PORT=5432
DB_NAME=country_quiz_db

3. Launch the app:
node index.js
```
Visit http://localhost:3000/ to take the quiz!


## Usage
•	Navigate to the root URL (/) to begin the quiz

•	Answer the country questions dynamically loaded from Postgres

•	Submit and view results based on your answers


## Project Structure

country_quiz/

├── public/                  # Static assets (CSS, JS, images)

├── views/                   # EJS templates

├── .env                     # Environment variables (ignored by Git)

├── .gitignore

├── index.js                 # Main server entry point

├── package.json

└── package-lock.json

## Environment Variables

--------------------------------------------------------
| Variable      | Description                          |
| ------------- | ------------------------------------ |
| `DB_USER`     | PostgreSQL username                  |
| `DB_PASSWORD` | PostgreSQL password                  |
| `DB_HOST`     | Host for the Postgres server         |
| `DB_PORT`     | Port for Postgres (e.g., 5432)       |
| `DB_NAME`     | The name of your quiz app’s database |
--------------------------------------------------------

## Author
Mridul