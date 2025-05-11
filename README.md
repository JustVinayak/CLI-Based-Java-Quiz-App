# Java CLI Quiz Application
A comprehensive CLI-based quiz application written in Java that offers a complete interactive learning and assessment experience. This robust platform combines user management, quiz creation, and performance tracking in an easy-to-use command-line interface.

## Features

- **User Account Management**
  - Login/Registration system
  - Password security
  - User profile management
  
- **Quiz Experience**
  - Browse available quizzes
  - Take quizzes with different question types
  - View detailed results after completion
  
- **Quiz Creation**
  - Design custom quizzes
  - Add multiple question types
  - Set difficulty levels
  
- **Question Types Support**
  - Multiple Choice Questions
  - True/False Questions
  - Fill in the Blank
  - Short Answer Questions
  
- **Difficulty System**
  - Easy, Medium, and Hard difficulty levels
  - Difficulty ratings for both quizzes and individual questions
  
- **Statistics and Tracking**
  - Performance history
  - Statistics by difficulty level
  - Comprehensive results analysis
  
- **Data Persistence**
  - SQLite database integration
  - Relational data structure
  - Session-to-session memory

## Requirements

- Java Development Kit (JDK) 8 or higher
- SQLite JDBC Driver
- Command-line interface

## Installation

1. Clone this repository or download the source code
```
git clone https://github.com/yourusername/java-cli-quiz-app.git
cd java-cli-quiz-app
```

2. Make sure the SQLite JDBC driver is in your classpath
```
# Example using Maven
mvn clean install
```

3. Compile the application
```
javac EnhancedQuizApplication.java
```

4. Run the application
```
java EnhancedQuizApplication
```

## Database Schema

The application uses an SQLite database with the following tables:
- `users`: User credentials and profile information
- `quizzes`: Quiz metadata including title, description, and difficulty
- `questions`: Question data with type and difficulty information
- `options`: Options for multiple-choice questions
- `answers`: Correct answers for different question types
- `quiz_attempts`: History of quiz attempts and performance

## Getting Started

1. Run the application using the instructions above
2. Register a new account or use the demo account:
   - Username: `admin`
   - Password: `admin123`
3. Navigate through the menu system using the number inputs
4. Try taking a sample quiz or creating your own

## Creating a Quiz

1. Select "Create Quiz" from the main menu
2. Enter quiz details including title, description, and overall difficulty
3. Add questions of various types:
   - For multiple choice: provide the question, options, and correct answer(s)
   - For true/false: provide the question and correct answer
   - For fill-in-blank: provide the question with a blank space and the correct answer
   - For short answer: provide the question and model answer(s)

## Demo Content

The application comes pre-loaded with sample quizzes on:
- Java Programming Basics
- Web Development Fundamentals

## Future Enhancements

- Timer functionality for timed quizzes
- Quiz categories and tags
- Export/import functionality for quizzes
- Enhanced reporting and analytics
- Multi-language support
