# Presentation Feedback System
A web application for managing and collecting feedback on software presentations. The system allows clients to rate presentations and representatives, while providing a dashboard for managing follow-ups.

# Features

   -Client feedback collection with star ratings
   -Multiple follow-up options:

   -New presentation scheduling
   -Quick call requests
   -Email information requests


   # Administrative dashboard for tracking:

   Presentation statistics
   Representative performance
   Follow-up status


Real-time updates
Comprehensive feedback management

# Tech Stack

# Frontend:

React
React Bootstrap
Axios for API calls
React Router for navigation


# Backend:

Node.js
Express
PostgreSQL database
CORS for cross-origin requests



# Prerequisites

Node.js (v14 or higher)
PostgreSQL (v12 or higher)
npm or yarn package manager

# Make sure to :
Create PostgreSQL database:

sqlCopyCREATE DATABASE presentation_feedback;

Set up database tables (using pgAdmin or psql):

Run the SQL scripts in src/backend/server/schema.sql

Configure database connection:

Update src/backend/server/config/db.js with your PostgreSQL credentials
