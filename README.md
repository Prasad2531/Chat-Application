# Chat Application with Spring Boot and Websockets

This project is a chat application built with Spring Boot and uses Websockets as communication medium.

## Technologies Used
![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=springboot&logoColor=fff)


![Screenshot 2024-04-23 115413](https://github.com/Prasad2531/Chat-Application/assets/92990670/213f091c-6ae1-421a-b564-9a8e7a529ba8)

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


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
