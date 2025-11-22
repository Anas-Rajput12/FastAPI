# FastAPI Banking Project

This is a simple banking API built with FastAPI.

## Setup and Installation

This project uses `uv` for package management.

1.  **Create a virtual environment:**
    ```bash
    uv venv
    ```

2.  **Activate the virtual environment:**
    - On Windows:
      ```bash
      .venv\Scripts\activate
      ```
    - On macOS/Linux:
      ```bash
      source .venv/bin/activate
      ```

3.  **Install dependencies:**
    ```bash
    uv pip install -r requirements.txt
    ```

## Running the Application

Once the dependencies are installed, you can run the application using `uvicorn`:

```bash
uvicorn main:app --reload
```

The API will be available at `http://127.0.0.1:8000`. You can access the interactive API documentation at `http://127.0.0.1:8000/docs`.
