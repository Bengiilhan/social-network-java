# social-network-java

## Project Overview
This project is an Advanced Object-Oriented Programming (AOOP) assignment that involves designing and implementing a simple Facebook-like social network using Java and various design patterns. The software runs on a single machine and allows users to create and manage social connections.

## Features
- User registration and authentication
- Friendship and other relationship management (family, colleagues, etc.)
- Privacy settings for search visibility
- User walls for posting text and links
- Groups and sub-groups management
- Predefined users and groups for testing

## Design Patterns Used
- Singleton Pattern
- Observer Pattern
- Adapter Pattern
- Memento Pattern

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```sh
   cd social-network-software
   ```
3. Build and run the project:
   ```sh
   javac -cp . *.java
   java Main
   ```

## Testing
- The project includes JUnit tests for selected components.
- To run tests, use:
  ```sh
  javac -cp .:junit-4.13.2.jar *.java
  java -cp .:junit-4.13.2.jar org.junit.runner.JUnitCore TestClassName
  ```

## Contribution
- Fork the repository
- Create a feature branch (`git checkout -b feature-branch`)
- Commit your changes (`git commit -m 'Add feature'`)
- Push to the branch (`git push origin feature-branch`)
- Create a pull request

## License
This project is licensed by MIT.

