# Pokémon Nexus Complete Project

## Local Setup & Run Instructions

To avoid browser security restrictions (CORS / origin blocks) when opening local HTML files directly via `file:///`, you should run a local server:

### 1. Start Backend API Server
- Run the [RUN_DJANGO_BACKEND_WINDOWS.bat](file:///c:/Users/simha/Downloads/Pokemon_Nexus_Complete_Project/Pokeman/RUN_DJANGO_BACKEND_WINDOWS.bat) file in Windows Explorer.
- This will install dependencies, run migrations, seed initial game achievements data, and host the API at `http://127.0.0.1:5000/`.

### 2. Start Frontend Server
- Run the [RUN_FRONTEND_LOCAL_SERVER.bat](file:///c:/Users/simha/Downloads/Pokemon_Nexus_Complete_Project/Pokeman/RUN_FRONTEND_LOCAL_SERVER.bat) file.
- This will start a local server at `http://localhost:8000/` and open your default browser automatically.

Now, all features (authentication, battles, inventory sync, achievements progress, and claiming rewards) will synchronize perfectly between the frontend on port 8000 and the backend on port 5000!
