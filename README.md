# MoodyFilm API

MoodyFilm API serves as the backend for the **MoodyFilm** platform, providing user authentication, movie recommendations, and comment functionalities.

## Features

- **User Authentication**: Secure login and registration using `bcrypt` and `jsonwebtoken`
- **Movie Data Management**: Fetch, store, and manage movie-related data
- **Comment System**: Allow users to leave comments and engage in discussions
- **Email Notifications**: Send notifications using `nodemailer`
- **CORS Support**: Cross-Origin Resource Sharing enabled for frontend integration

## Technologies Used

- **Backend Framework**: Express.js
- **Database**: MongoDB (Mongoose ODM)
- **Authentication**: NextAuth, JSON Web Tokens (JWT), bcrypt
- **Email Service**: Nodemailer
- **Web Scraping**: Cheerio & JSDOM
- **File Handling**: FS-Extra & Fluent-FFmpeg
- **Environment Variables**: dotenv

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/moodyfilm-api.git
   cd moodyfilm-api
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create a `.env` file and add the following environment variables:
   ```sh
   MONGODB_CREDENTIALS="mongodb+srv://your-username:your-password@your-cluster.mongodb.net/FilmDb"
   BACKEND_URL="https://refactosdfsaadle.vercel.app"
   FRONTEND_URL="https://moodyfilm.netlify.app/"
   MAIL_USER_ARYAN="aryan03aryansingh@gmail.com"
   MAIL_PASS_ARYAN="your-email-password"
   NEXTAUTH_SECRET="adf23dfsf3asdarn2q3r23jr"
   ```
4. Start the server:
   ```sh
   npm start
   ```

  
## Contribution

Feel free to contribute by submitting issues or pull requests.

## License

This project is licensed under the MIT License.

---

Developed with ❤️ by MoodyFilm Team
