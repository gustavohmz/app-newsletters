# Newsletter App Dashboard

This front-end project, developed with Angular CLI, provides a control panel for managing newsletters. Administrators can create newsletters, attach PDF files and images, and send personalized HTML-formatted emails to subscribers. The Tiny library was utilized for creating HTML templates for emails.

## Docker Execution

This project includes a Dockerfile to facilitate the creation of a container.

```bash
docker build -t app-newsletters-front .
docker run -d -p 4200:80 app-newsletters-front
```

## Accessing the Application Interface

Access the application interface at http://localhost:4200/.

## Features

In the application, we have:

- **Subscription view**
- **Newsletter listing view**
- **Newsletter editing view**
- **Subscription cancellation view**

The project is structured using a modular architecture in Angular, including core, feature, and shared modules.
