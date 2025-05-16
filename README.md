# Merkle Tree in Python
This Python notebook demonstrates an attempt at how to create a Merkle tree, generate Merkle proofs, and verify them for a list of data items (e.g., transactions). It’s designed for educational purposes to understand Merkle trees in blockchains.

## Prerequisites
- Python 3.9 or higher

## Installation and Setup
### 1. Install Python:
- Download and install Python from python.org. (ensure 3.9 and above)
- Verify installation: python --version or python3 --version.
### 2. Create a Virtual Environment:
- Open a terminal in the project directory.
- Create a virtual environment:
```bash
python -m venv venv
```
- Activate the virtual environment:
- Windows: `venv\Scripts\activate`
- macOS/Linux: `source venv/bin/activate`
### 3. Install Dependencies:
- The notebook uses the standard library (hashlib) and other inbuilt Python libraries since Python 3.9. No additional libraries are required.

## Using the Notebook
- Open the notebook (merkle_tree.ipynb) in Jupyter Notebook or any IDE which supports Jupyter Notebook format.
- Run the cells to:
  - Create a Merkle tree from a list of strings.
  - Generate a Merkle proof for a specific item.
  - Verify the proof against the Merkle root.
  - Modify the data list in the main section to test with your own data.
