# Noteful server

An API for the Bookmarks client supporting GET, POST, DELETE, PATCH.

## Set up

Complete the following steps to start noteful-server:

1. Install the node dependencies `npm install`
2. Run database migrations `npm run migrate`
3. Seed database with dummy data `psql -U dunder_mifflin -d blogful -f ./seeds/seed.blogful_articles.sql`
4. Start nodemon for the application `npm run dev`

## Scripts

Start the application `npm start`

Start nodemon for the application `npm run dev`

Run the tests `npm test`

## Deploying

When your new project is ready for deployment, add a new Heroku application with `heroku create`. This will make a new git remote called "heroku" and you can then `npm run deploy` which will push this remote's master branch.