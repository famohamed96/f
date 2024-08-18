# Web Forum

This project is a web forum that allows users to communicate, create posts and comments, like/dislike posts and comments, and filter posts based on categories.

## Objectives

- Enable communication between users.
- Associate categories with posts.
- Implement liking and disliking posts and comments.
- Provide a filtering mechanism for posts.
- Use SQLite for data storage.
- Implement user authentication with sessions and cookies.
- Handle user registration and login securely.
- Implement posts and comments functionality for registered users.
- Allow filtering posts by categories, created posts, and liked posts.
- Use Docker for containerization.

## Technologies Used

- Go
- SQLite
- UUID
- Docker

## Installation and Setup

1. Clone the repository:

```bash
git clone <https://learn.reboot01.com/git/malkhoza/forum>
cd forum
```

2. Install required dependencies

```bash
go get github.com/mattn/go-sqlite3
go get golang.org/x/crypto/bcrypt
```

3. Build and run the application using Docker:

```bash
docker build -t web-forum .
docker run -p 8080:8080 web-forum
```
3. Build and run the application using Docker:

	Access the forum in your browser at http://localhost:8080.


## Database Setup
The SQLite database will be automatically created when the application is run.

## Usage
* Register as a new user on the forum by providing email, username, and password.
* Log in to access the forum and create posts and comments.
* Associate categories with posts during creation.
* Like or dislike posts and comments.
* Use the filter mechanism to view posts by categories, created posts, or liked posts.
