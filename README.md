# Multilanguage_translation
// Deployment Configuration
// Install necessary dependencies globally
// npm install -g pm2

// Start the application using PM2 for production
// pm2 start server.js --name faq-api
// pm2 save
// pm2 startup

// Environment Variables Setup (.env file)
// MONGO_URI=<your-mongodb-uri>
// GOOGLE_TRANSLATE_API_KEY=<your-google-api-key>
// REDIS_HOST=<your-redis-host>
// REDIS_PORT=<your-redis-port>

// Deploying to Heroku
// - Install Heroku CLI: https://devcenter.heroku.com/articles/heroku-cli
// - Run: `heroku login`
// - Create a new Heroku app: `heroku create faq-api`
// - Add MongoDB (e.g., using MongoDB Atlas or Heroku Add-ons)
// - Set environment variables: `heroku config:set MONGO_URI=<your-mongodb-uri>`
// - Deploy: `git push heroku main`

// Deploying to AWS (Using EC2 and Docker)
// - Launch an EC2 instance with Node.js & MongoDB setup
// - Install Docker: `sudo apt-get install docker.io`
// - Transfer project files: `scp -r . user@ec2-instance:/home/ubuntu/faq-api`
// - SSH into instance: `ssh user@ec2-instance`
// - Run Docker Compose: `docker-compose up --build -d`

![Screenshot 2025-02-01 225443](https://github.com/user-attachments/assets/47b50ca6-315b-4160-a1a6-9d9c76c865e6)
