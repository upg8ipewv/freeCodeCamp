# Secret keys and configuration for freeCodeCamp

# Base API URL
API_LOCATION=http://localhost:3000

# Home location for the client app
HOME_LOCATION=http://localhost:8000

# MongoDB connection URI (default local port: 27017)
MONGOHQ_URL=mongodb://localhost:27017/freecodecamp

# Cookie and session secrets (use random strings in production)
SESSION_SECRET=a_very_secret_key_change_me
JWT_SECRET=another_very_secret_key_change_me
COOKIE_SECRET=cookie_secret_change_me

# Node Environment (development | production | test)
NODE_ENV=development