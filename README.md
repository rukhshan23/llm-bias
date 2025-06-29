# llm-bias

This repository contains code and data analyzing bias in large language models—specifically biases related to neurodiverse/autistic communication styles. Follow the instructions below to reproduce our analysis.

---

## 1. Clone the Repository

- Clone this repo using the following command:

    git clone https://github.com/rukhshan23/llm-bias.git
  
---

## 2. Create and Activate a Python Virtual Environment

- Create a virtual environment in the project root directory:

    python3 -m venv .venv

- Activate the virtual environment:

    On macOS/Linux:  
    source .venv/bin/activate

    On Windows:  
    .venv\Scripts\activate

---

## 3. Install Dependencies

- Run the following command to install all necessary dependencies:

    pip install -r requirements.txt

---

## 4. Set Environment Variables

- Set the required environment variables before running the code.

    On macOS/Linux:  
    export LLM_API_KEY=your_key_here  
    export LLM_ENDPOINT=https://your-llm-api-url

    On Windows (Command Prompt):  
    set LLM_API_KEY=your_key_here  
    set LLM_ENDPOINT=https://your-llm-api-url

---

## 5. Open Notebooks in VS Code and Select the Correct Kernel

If you are using Visual Studio Code:

1. Open the Command Palette (`Cmd+Shift+P` on macOS or `Ctrl+Shift+P` on Windows/Linux).
2. Select the option `Python: Select Interpreter`.
3. Choose the interpreter that points to your `.venv` folder (e.g., `.venv/bin/python` or `.venv\Scripts\python.exe`).

---

## 6. Run the Notebook

- The repository includes pre-generated data. You do **not** need to rerun cells that regenerate data.
- You can directly open the notebooks and begin your analysis.

---

Let me know if you’d like to add a License, Citation, or Contribution section.
