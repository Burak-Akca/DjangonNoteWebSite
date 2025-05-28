# 📝 Django Notes App

**A simple and clean note-taking application built with Django, containerized using Docker Compose.**

---

## ✨ Features

- Create, edit, and delete notes easily
- No user authentication—start using immediately
- Fully dockerized for hassle-free deployment

---

## 🗂️ Project Structure

| File/Folder            | Description                                   |
|------------------------|-----------------------------------------------|
| `.dockerignore`        | Files and directories ignored by Docker       |
| `CODE_OF_CONDUCT.md`   | Guidelines for contributor behavior           |
| `CONTRIBUTING.md`      | How to contribute to the project              |
| `Dockerfile`           | Instructions to build the Docker image        |
| `LICENSE`              | License information (MIT License)             |
| `README.md`            | Project documentation                         |
| `compose.yaml`         | Docker Compose configuration file             |
| `src/`                 | Django project source code                    |

---

## 🐳 Running with Docker Compose

Make sure [Docker](https://www.docker.com/) and [Docker Compose](https://docs.docker.com/compose/) are installed on your machine.

```bash
docker compose up --build -d
```

Open your browser at http://localhost:8001/ to start using the app.

---

## 📝 Usage

- Visit the homepage (`/`) to see your notes  
- Add a new note at `/new/`  
- Edit or delete notes from the list  

---

## 📄 License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## 🤝 Contributing

Contributions and issues are welcome! Please check CONTRIBUTING.md to get started.
