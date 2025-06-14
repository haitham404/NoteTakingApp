# Note Taking Application

A Java-based desktop application for managing and organizing notes with secure features.

## Features

- 📝 Create and manage notes
- 🔒 Secure note functionality
- 👤 User authentication system
- 💾 File management system
- 🎨 User-friendly interface
- 🔐 Secure user management

## Tech Stack

- Java
- Java Swing (GUI)
- File I/O for data persistence

## Project Structure

```
src/
├── Main.java              # Application entry point
├── NoteApp.java           # Main application logic
├── Note.java             # Note data model
├── SecureNote.java       # Secure note implementation
├── User.java             # User data model
├── UserManager.java      # User management system
├── FileManager.java      # File handling system
├── Controller.java       # Application controller
├── LoginScreen.java      # Login interface
├── SignUpScreen.java     # Registration interface
└── WelcomeScreen.java    # Welcome interface
```

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- Java Runtime Environment (JRE)

### Running the Application

1. Compile the Java files:
```bash
javac *.java
```

2. Run the application:
```bash
java Main
```

## Features in Detail

### Note Management
- Create new notes
- Edit existing notes
- Delete notes
- View note history

### Security Features
- User authentication
- Secure note storage
- Password protection
- User session management

### User Interface
- Login screen
- Registration screen
- Welcome screen
- Note management interface

## Development

This application is built using Java Swing for the graphical user interface and implements a MVC (Model-View-Controller) architecture pattern.

## License

This project is licensed under the MIT License. 