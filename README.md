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
2. Run ```uv venv``` to create a virtual environment
3. Run ```./.venv/Scripts/activate``` (Windows) or ```source ./.venv/bin/activate``` (MacOS) to activate the virtual environment
4. Run ```uv sync``` to install dependencies
5. Run ```cp .env.example .env``` and follow the instruction inside to get the required variables
6. Open **notebook.ipynb** and change kernel to venv
7. Run each cell to ingest documents