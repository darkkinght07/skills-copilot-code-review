---
applyTo: "src/backend/**/*,src/app.py"
---

## Backend Guidelines

- All API endpoints must be defined in the `routers` folder.
- Load example database content from the `database.py` file.
- Return safe, user-friendly error messages to the frontend, log detailed error information on the server, and avoid exposing sensitive internal errors or stack traces.
- Ensure all APIs are explained in the documentation.
- Verify changes in the backend are reflected in the frontend (`src/static/**`). If possible breaking changes are found, mention them to the developer.