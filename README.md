# ANN-MNIST

A simple Artificial Neural Network (ANN) project for classifying handwritten digits from the MNIST dataset using PyTorch.

## Project Structure
- `notebooks/` - Jupyter notebooks for experiments and analysis
- `models/` - Saved model weights
- `outputs/` - Output files (e.g., plots)
- `data/` - MNIST data (not included in repo)

## Setup
1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd ANN-MNIST
   ```
2. (Recommended) Create and activate a virtual environment:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
- Open and run the Jupyter notebooks in the `notebooks/` directory to train and evaluate the ANN on MNIST.
- Model weights and outputs will be saved in their respective folders.

## Notes
- The `data/`, `models/`, and `outputs/` directories are excluded from version control.
- Download the MNIST dataset as instructed in the notebooks if not already present. 