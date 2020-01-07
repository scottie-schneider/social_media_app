## Getting Started

1. Clone this repo with `git clone https://github.com/scottie-schneider/social_media_app.git`
2. Install dependencies (`npm install` or `yarn install`)
3. Go to [MLab](mlab.com) and create a new (free) database
4. Copy the Database URI to connect using the Mongo Driver
5. Change your .env.default file to just .env and paste the copied uri as the value for MONGO_URI in .env
6. Add any random string for the SESSION_SECRET entry in your .env file
7. Run with `npm run dev` or `yarn dev`
8. Server should be listening on localhost:3000

Note: I coded this project while taking Reed Barker's amazing NextJS course. Credit goes to him for the architecture. Thanks Reed!

https://www.udemy.com/user/reed-barger/ 