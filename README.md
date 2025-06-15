## Prerequisites
- Python >= 3.11
- uv (install using pip install uv or https://docs.astral.sh/uv/)

## Project structure
~~~
.
├── files/
│   ├── pdf/        # Place input PDFs here
│   ├── md/         # Converted markdown files
│   ├── chunks/     # Split text chunks
│   └── embeddings/ # Generated embeddings
├── notebook.ipynb  # This notebook
└── .env            # Please make a copy from .env.example
~~~

## Running the project
1. Install prereqisites
2. Run ```uv venv``` to create the virtual environment
3. Run ```uv sync``` to install dependencies
4. Run ```cp .env.example .env``` and follow the instruction inside to get the required variables
5. Open **notebook.ipynb** and change kernel to venv
6. Run each cell to ingest documents