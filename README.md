# bank-fraud-detection
## Setup Instructions

1. **Create a virtual environment:**
    ```bash
    python3 -m venv venv
    ```

2. **Activate the virtual environment:**
    - On macOS and Linux:
      ```bash
      source venv/bin/activate
      ```
    - On Windows:
      ```bash
      .\venv\Scripts\activate
      ```

3. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Connect the virtual environment to Jupyter Notebook:**
    ```bash
    python -m ipykernel install --user --name=venv
    ```

5. **Start Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

6. **Select the virtual environment kernel in Jupyter Notebook:**
    - Open a notebook.
    - Go to `Kernel` > `Change kernel` > `venv`.