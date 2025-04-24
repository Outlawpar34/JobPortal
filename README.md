## Django Job Portal

#### An open source online job portal.

### Getting Started

Follow these steps to set up and run the project locally:

#### Prerequisites
- Python (version 3.10.0)
- pip (Python package manager)
- Virtualenv (optional but recommended)

#### Setup Instructions

1. **Clone the Repository**
    ```bash
    git clone https://github.com/Outlawpar34/JobPortal
    cd JobPortal
    ```

2. **Create and Activate a Virtual Environment**
    - On Windows:
      ```bash
      python -m venv env
      env\Scripts\activate
      ```
    - On macOS/Linux:
      ```bash
      python3 -m venv env
      source env/bin/activate
      ```

3. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4. **Apply Migrations**
    ```bash
    python manage.py migrate
    ```

5. **Run the Development Server**
    ```bash
    python manage.py runserver
    ```

6. **Access the Application**
    Open your browser and navigate to `http://127.0.0.1:8000/`.

#### Deactivating the Virtual Environment
When you're done, deactivate the virtual environment by running:
```bash
deactivate
```
