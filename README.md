## Family Tracker

## Overview
Family Tracker is a web application that allows you and your family members to color-code the world map based on the places you have visited. It provides a visual representation of your travels and helps you keep track of your family’s global adventures.

## Table of Contents
- Features
- Installation
- Usage
- Technologies Used

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
   ```sh
   
  git clone https://github.com/Kirtikaa25/travel_record
  
  cd travel_record

## Navigate to the backend directory and install dependencies:
sh

Copy code

cd backend

npm install

## Create a .env file in the backend directory and add the following variables:

env

Copy code

DATABASE_URL=postgres://username:password@localhost:5432/yourdatabase

SESSION_SECRET=your_session_secret

## Start the backend server:

sh

Copy code

npm start

## Frontend Setup
The frontend part of this project is integrated with the backend using EJS templates.

Visit http://localhost:3000 in your web browser.

Register or log in to your account.

Start coloring the map by selecting the countries you have visited.
View your family’s aggregated travel map.
## This is what you'll end up with

