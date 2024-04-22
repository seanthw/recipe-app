# React-Node Recipe App
#Getting Started
## Prerequisites
    - Node.js and npm installed on your machine.
    - An account on ElephantSQL (https://www.elephantsql.com/) for the database.
    - A Spoonacular (https://spoonacular.com/food-api) API key for the recipe API

# 1. Clone the Repository:
    git clone https://github.com/seanthw/recipe-app.git
    - cd recipe-app

# 2. Setting up the Backend:
      Navigate to the backend directory:
      - cd backend
      - npm install

     Spoonacular API:
      Add the api key to the API_KEY variable in the .env file


     ElephantSQL Setup:
      - Create a new database instance on ElephantSQL.
      - Copy the connection string provided by ElephantSQL.
     
     Prisma Setup:
       Replace the DATABASE_URL in the .env file with your ElephantSQL connection string.
       Initialize Prisma and generate the Prisma client:
           - npx prisma init
           - npx prisma generate

     Start the backend server:
           - npm start

# 3. Setting up the Frontend:
     Navigate to the frontend directory:
      - cd frontend
     Install the necessary packages:
      - npm install
     Start the frontend development server:
      - npm run dev
