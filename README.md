# Chatify: Building a Modern Chat Application

## Project Overview
Chatify is a modern web-based chat application designed to facilitate real-time communication between users. This platform allows users to join chat rooms, send and receive messages, and manage their profiles.

## Features
- **User Registration and Authentication**: Users can create accounts and log in securely.
- **Chat Rooms**: Create or join chat rooms based on interests.
- **Real-time Messaging**: Instant communication with users in the same chat room.
- **Message History**: View previous conversations.
- **Typing Indicators**: See when other users are typing.
- **Notifications**: Receive alerts for new messages or mentions.
- **Security**: Data encryption ensures user privacy.
- **User Profiles**: Users can customize their profiles with personal information and avatars.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL
- **Development Tools**: Visual Studio Code

## System Requirements
- **Hardware**: 
  - Processor: i3 or above
  - RAM: 4 GB or more
- **Software**:
  - OS: Windows 11
  - Development environment: Visual Studio Code
  - Local server: XAMPP/WAMP

## Installation

1. **Clone the Repository**:
   - Open your terminal or command prompt.
   - Run the following command to clone the repository:
     ```bash
     git clone https://github.com/username/chatify.git
     ```

2. **Install XAMPP/WAMP**:
   - Download and install [XAMPP](https://www.apachefriends.org/index.html) or [WAMP](https://www.wampserver.com/en/) to set up a local server environment with Apache and MySQL.

3. **Move Project Files**:
   - After downloading/cloning the project, move the project folder to the `htdocs` directory (for XAMPP) or the `www` directory (for WAMP).
     - For XAMPP, move the folder to:
       ```
       C:\xampp\htdocs\chatify
       ```
     - For WAMP, move the folder to:
       ```
       C:\wamp64\www\chatify
       ```

## Setup

1. **Start XAMPP/WAMP Services**:
   - Open XAMPP or WAMP and start the **Apache** and **MySQL** services.

2. **Create Database in MySQL**:
   - Open your browser and navigate to `http://localhost/phpmyadmin`.
   - Create a new database called `chatify`.
   - Import the provided `chatify.sql` file (which contains the database structure and sample data) into this database.

3. **Configure Database Connection**:
   - Open the project folder and navigate to the `php/config.php` file.
   - Edit the following lines to match your local database setup:
     ```php
     $hostname = "localhost";
     $username = "root"; // Default username for XAMPP/WAMP
     $password = "";      // Leave this blank if you haven't set a MySQL password
     $dbname = "chatify"; // Name of the database you created
     ```
   - Save the file.

4. **Open the Application in Your Browser**:
   - Once the database is set up and configured, open your browser and type the following URL to access the chat application:
     ```
     http://localhost/chatify
     ```

5. **Sign Up and Start Using the Chat Application**:
   - You should be able to see the Chatify homepage.
   - Create a new account by signing up, and start using the chat application by creating or joining chat rooms.

## Future Enhancements
- **Voice and Video Chat**: Expanding the app to support multimedia communication.
- **AI-Powered Chatbots**: Integration of bots for customer service and automated responses.
- **Better User Experience**: Adding features like themes, customizable notifications, and more.

## Limitations
- **Limited Multimedia Support**: The current version is text-based and lacks features for sharing multimedia files.
- **Group Chat Management**: Handling large groups could become challenging without further optimizations.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Authors
- **Keerthan**  
- **Rohan**  
- **Rohini R Kundapur**

---