# Online Compiler

An Online Compiler built using the MERN stack that allows users to write, compile, and run code. This project includes a custom isolator for sandboxing user-submitted code using Docker containers.

## Features

- **Online Compiler**: Write, compile, and run code.
- **Custom Isolator**: (Sandboxing) Executing user-submitted code in isolated Docker containers with limited permissions and resources. Docker containers provide a level of isolation that helps mitigate the impact of malicious code by containing any harmful effects within the container.
- **Admin Functionality**: Admins can manage user submissions and monitor system performance.
- **Authentication & Authorization**: Utilizes JWT (JSON Web Tokens) for secure access.

## Tech Stack

- **Frontend**: React.js for UI.
- **Backend**: Node.js and Express.js for building RESTful APIs.
- **Containerization**: Docker for isolating and executing user code.
