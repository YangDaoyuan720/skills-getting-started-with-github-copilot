# GitHub Copilot Workspace Instructions

## Overview
This workspace is a simple FastAPI application for managing extracurricular activities at Mergington High School. It is designed for learning and experimenting with GitHub Copilot and related AI coding tools.

## Build & Run
- **Install dependencies:**
  ```
  pip install fastapi uvicorn
  ```
- **Run the app:**
  ```
  python src/app.py
  ```
- **API Docs:**
  - Swagger: http://localhost:8000/docs
  - Redoc: http://localhost:8000/redoc

## Project Structure
- `src/app.py`: Main FastAPI application
- `src/static/`: Frontend static files (HTML, JS, CSS)
- `src/README.md`: API and usage documentation

## Conventions & Tips
- Use meaningful identifiers for activities and participants.
- Keep backend and frontend code separated (see `src/static/`).
- Prefer FastAPI best practices for endpoints and data models.
- Use the provided README files for reference.

## Potential Pitfalls
- Ensure all dependencies are installed before running.
- If port 8000 is in use, change the port in the run command.
- Static files must be served from the correct directory.

## Example Prompts
- "Add a new API endpoint to delete an activity."
- "Improve error handling for signup failures."
- "Add a frontend form for activity signup."

## Next Steps: Agent Customization
- Consider creating an agent customization to:
  - Enforce API naming conventions
  - Auto-generate OpenAPI docs
  - Separate frontend/backend instructions using `applyTo`

For more advanced customization, see the [FastAPI documentation](https://fastapi.tiangolo.com/) and [GitHub Copilot agent customization guide](https://docs.github.com/en/copilot).
