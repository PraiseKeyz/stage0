## Public API - Email, CurrentTime, and GitHub URL

This is a simple public API built using Node.js, Express.js, and CORS. The API returns a JSON response containing an email address, the current datetime, and a GitHub URL.

Features
- Returns a JSON response with an email address, current datetime, and GitHub URL.
- Supports CORS to allow cross-origin requests.
- Lightweight and easy to use.

Setup Instructions

Prerequisites
Ensure you have Node.js and npm installed on your system.

Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/PraiseKeyz/stage0
   cd stage0
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the server:
   ```sh
   node server.js
   ```
   The server will start on `http://localhost:3000` by default.

## API Documentation

### Endpoint: Get API Response
- URL: `/api`
- Method: `GET`
- Response Format: `JSON`
- Example Response:
  ```json
  {
    "email": "praiseoluwatobilobaadebayo@gmail.com",
    "current_datetime": "2025-02-03T12:00:00Z",
    "github_url": "https://github.com/PraiseKeyz/stage0"
  }
  ```

Deployment:

To deploy this API on a platform like Render, Railway, or Heroku:
1. Push the project to a GitHub repository.
2. Connect the repository to your chosen deployment service.
3. Set up environment variables if needed.
4. Deploy and obtain your live API URL.

Technologies Used
- Node.js
- Express.js
- CORS

License
This project is open-source and available under the MIT License.

Author
Developed by Praisekeyz https://github.com/PraiseKeyz.

