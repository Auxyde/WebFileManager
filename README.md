# WebFileManager

## Overview
WebFileManager is a PHP-based web application for managing files. It's built using Symfony and Docker, providing a robust and scalable solution for file management tasks.

## Features
- **File Management**: Upload, download, delete, and organize files.
- **User Authentication**: Secure access with user accounts.
- **Docker Integration**: Easy deployment and scalability.
- **Symfony Framework**: Leveraging Symfony for a structured and efficient codebase.

## Prerequisites
- Docker
- Docker Compose
- PHP 8.0 or higher
- Composer

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Auxyde/WebFileManager.git
   cd WebFileManager
   ```
2. **Build and Run with Docker**:
   ```bash
   docker-compose up --build
   ```
3. **Install Dependencies**:
   ```bash
   composer install
   ```

## Configuration
- **Doctrine Configuration**: Adjust `config/packages/doctrine.yaml` for database settings.
- **Security**: Configure `config/packages/security.yaml` for security settings.

## Usage
- Access the web interface at `http://localhost:8000`.
- Log in using your credentials to manage files.

## Testing
- Run tests using:
  ```bash
  php bin/phpunit
  ```

## Documentation
- Further documentation is available in the `docs/` directory.

## Contributing
Contributions are welcome. Please follow the standard GitHub pull request process.

## License
This project is licensed under the MIT License.

## Acknowledgements
- Symfony Community
- Docker Team

## Alignment with RNCP Competences of BUT

WebFileManager exemplifies several competences from the RNCP for the "Développeur Web et Web Mobile" program:

- **Conception and Development of Web Applications**: 
  - This project is a fully functional web application, showcasing front-end and back-end development skills. It demonstrates the ability to create user interfaces and manage server-side logic, aligning with the core competencies of web application development.

- **Database Management**: 
  - The application uses a Postgres database to manage user data and file metadata. This reflects competence in database design, implementation, and management, crucial for modern web development.

- **Implementation of Appropriate Security Measures**: 
  - Security is a key aspect of WebFileManager, especially in handling file uploads and user authentication. Implementing security measures to protect user data and manage file access (private or public) aligns with the program's focus on web application security.

- **Adaptation to New Technologies and Methodologies**: 
  - The project demonstrates adaptability and proficiency in using contemporary web technologies and methodologies, such as Docker for deployment and Symfony framework for development.

- **File Management and Sharing Features**:
  - Users can upload files (up to 100MB) and choose to keep them private or share them with others. This feature demonstrates an understanding of file handling and user-centric design in web applications.

This project serves as a practical showcase of the skills and knowledge acquired in the BUT program, particularly in web development and database management.
