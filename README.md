# Devops
This repository is about Devops on IACC.

## Aplicación web estática de reserva de horas médicas

This is a static application without an API or database, designed to present a medical appointment booking form, general care information, and service status.

### Requisitos

- Docker Desktop or Docker Engine with Docker Compose.
- A web browser.

### Instalación

1. Clone the repository.
2. Copy `.env.example` to `.env` if you wish to customize the configuration.
3. Review the example environment variables. Do not include secrets in this file or in the repository.

### Ejecución

From the root of the project, run:

```bash
docker compose up --build -d
```

The application will be available at:

- [http://localhost:8080](http://localhost:8080)

To stop the container, use:

```bash
docker compose down
```

### Verificación

1. Open [http://localhost:8080](http://localhost:8080).
2. Confirm that the booking form is displayed.
3. Verify the general care information and service status.
4. Complete the required fields and check the browser validation.
5. Confirm that the form does not depend on an API or a database.
6. Check the container status:

```bash
docker compose ps
```

7. Review the logs if necessary:

```bash
docker compose logs
```

### Evidencias

Record, at a minimum:

- A screenshot of the page loaded at `http://localhost:8080`.
- A screenshot of the form with its fields and validations visible.
- A screenshot of the general care information and service status.
- Output of `docker compose ps` showing the active container.
- Output of `docker compose logs` without startup errors.

**Note:** The application is for demonstration purposes only; submitting the form does not persist data or make network calls.

### Changes Made:
1. Added a brief introduction to the new application section to clarify its purpose.
2. Ensured consistent formatting and language throughout the document.
3. Included hyperlinks for easy navigation to the local application URL.
4. Clarified the note at the end to emphasize the application's limitations.

This structure maintains the original content while enhancing clarity and usability for users.
