### TRAVEL RECORD

## Overview
Travel Record is a web application that allows you and your family members to color-code the world map based on the places you have visited. It provides a visual representation of your travels and helps you keep track of your family’s global adventures.

## Table of Contents
- Features
- Installation
- Usage
- Technologies Used - Node,Express,EJS,PostgreSQL

## Features
- User authentication
- Individual user maps with color-coded countries
- Family map that aggregates all members’ travels
- Responsive design

## Installation

### Prerequisites
- Node.js
- PostgreSQL

### Backend Setup
1. Clone the repository:
2. git clone https://github.com/Kirtikaa25/travel_record
3. cd travel_record

## Navigate to the backend directory and install dependencies:

cd backend

npm install

## Create a .env file in the backend directory and add the following variables:

DATABASE_URL=postgres://username:password@localhost:5432/yourdatabase

SESSION_SECRET=your_session_secret

## Initialize the PostgreSQL database and run migrations (ensure you have a migrations setup):

npx sequelize-cli db:migrate

## Start the backend server:

npm start

## Frontend Setup
The frontend part of this project is integrated with the backend using EJS templates.

Visit http://localhost:3000 in your web browser.
Start coloring the map by selecting the countries you have visited.
View your family’s aggregated travel map.
## This is what you'll end up with

![f54e9d2b-34a0-4d57-8b3e-531112cbc2b0](https://github.com/Kirtikaa25/travel_record/assets/100124517/cc011675-a791-49ce-a198-77a22d79f00f)
![8169ffec-fbae-4588-8b43-2fda01e7dbe9](https://github.com/Kirtikaa25/travel_record/assets/100124517/e2392777-85fa-48a9-ba6c-0e751913912c)
