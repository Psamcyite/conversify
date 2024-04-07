
**Conversify**

### Features

- **Real-time Chat**: Engage in real-time conversations with other users.
- **User Authentication**: Secure user authentication using JWT.
- **Private Messaging**: Send private messages to individual users.
- **Online Presence**: See when other users are online.
- **Message History**: Access chat history for ongoing conversations.

### Technologies Used

- **MongoDB**: NoSQL database for storing user data and chat messages.
- **Express.js**: Web application framework for Node.js used for building the server.
- **React.js**: JavaScript library for building user interfaces.
- **Node.js**: JavaScript runtime environment for running server-side code.
- **JWT (JSON Web Tokens)**: Secure authentication mechanism.
- **Socket.IO**: Real-time bidirectional event-based communication.

### Prerequisites

- Node.js installed on your machine
- MongoDB installed locally or accessible via a MongoDB Atlas cluster
- Git installed on your machine

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Conversify.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Conversify
   ```

3. Install server dependencies:

   ```bash
   npm install
   ```

4. Navigate to the client directory:

   ```bash
   cd client
   ```

5. Install client dependencies:

   ```bash
   npm install
   ```

6. Navigate back to the project root:

   ```bash
   cd ..
   ```

7. Create a `.env` file in the root directory and configure environment variables:

   ```plaintext
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/conversify
   JWT_SECRET=your-secret-key
   ```

8. Run the development server:

   ```bash
   npm run dev
   ```

9. Navigate to `http://localhost:3000` in your web browser to access the application.

### Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Acknowledgements

- Inspired by [MERN Stack Tutorial with Socket.IO](https://www.youtube.com/watch?v=KlcEYomuD4E) by JavaScript Mastery.

### Contact

For inquiries, please contact [psamcyitedev@gmail.com](mailto:psamcyitedev@gmail.com).
