# Chat Application with Spring Boot and Websockets

This project is a chat application built with Spring Boot and uses Websockets as communication medium.

## Installation

1. **Prerequisites**: 
   - Java 11 or higher
   - Maven (for building the project)

2. **Running the Application**:
   - Clone the repository:
     ```sh
     git clone <repository-url>
     ```

   - Build the project:
     ```sh
     cd chat-application
     mvn clean package
     ```

   - Run the Spring Boot application:
     ```sh
     java -jar target/chat-application.jar
     ```

3. **Accessing the Application**:
   - Open a web browser and navigate to [http://localhost:8080](http://localhost:8080).

## Usage

- Open multiple browser tabs or devices to simulate multiple users.
- Start chatting with other users in real-time.

## Project Structure

- `src/main/java/com/example/chat/`: Contains the main application code.
  - `ChatController.java`: Defines the REST endpoints for the chat application.
  - `ChatService.java`: Implements the business logic for the chat functionality.
  - `WebSocketConfig.java`: Configures the Websocket endpoint and message broker.

- `src/main/resources/`: Contains application properties and static resources.

## Configuration

Application configurations can be modified in `src/main/resources/application.properties`.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
