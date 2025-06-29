# llm-bias

This file contains code and data analysizing bias in large language models; this bias is related to neurodiverse/autistic communication styles. Follow these instructions to reproduce our analysis:

### 1. Clone the Repository.

### 2. Create a Python Virtual Environment Inside the Repository's Root Folder After Cloning it, and then activate it.

python3 -m venv .venv
source .venv/bin/activate  # On macOS/Linux
# OR
.venv\Scripts\activate     # On Windows

### 3. Install Dependencies

pip3 install -r requirements.txt

### 4. Set Environment Variables

# # On macOS/Linux
export LLM_API_KEY=your_key_here
export LLM_ENDPOINT=https://your-llm-api-url
# OR
set LLM_API_KEY=your_key_here
set LLM_ENDPOINT=https://your-llm-api-url

### 5. Open any Notebook via VS Code, and Make Sure to Select the Correct Python Kernel in VS.

If you're using VS Code, make sure to select the Python interpreter from the virtual environment you created:

1. Open the Command Palette (`Cmd+Shift+P` on macOS or `Ctrl+Shift+P` on Windows/Linux).
2. Type and select: `Python: Select Interpreter`.
3. Choose the interpreter that points to your `.venv` folder (e.g., `.venv/bin/python` or `.venv\Scripts\python.exe`).

This ensures that Jupyter notebooks and scripts use the correct environment.

### 6. Run the cells as needed. You do not need to run the cells that regenerate data, as the data is already saved in the repo from a previous run.
