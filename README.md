# Classification Algorithms

This repository contains example implementations and demos of simple classification algorithms (Jupyter notebooks):

- KNN.ipynb — Custom K-Nearest Neighbors implementation with synthetic datasets, visualizations, and experiments (k selection).
- Backpropagation_Logic_Gates_&_Linear_data.ipynb — Small feedforward network for logic gates and a linear regression demo.

## Requirements

Install dependencies (macOS / terminal):
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Example requirements (if you don't have a file):
```
numpy
matplotlib
scikit-learn
jupyter
```

## Usage

Open and run the notebooks with Jupyter:
```bash
jupyter lab
# or
jupyter notebook
```

Execute a notebook headless:
```bash
jupyter nbconvert --to notebook --execute KNN.ipynb --output executed_KNN.ipynb
```

## Notes

- KNN.ipynb defines a minimal `KNearestNeighbors` class (fit, predict, predict_proba) and includes plotting for three synthetic datasets.
- The backpropagation notebook shows a tiny neural network for AND/OR/XOR examples and a linear regression toy example.

## Contributing

- Add improvements on a feature branch and open a pull request.
- Include tests or example runs for reproducibility.

## License

Add a LICENSE file or specify a license before distributing.
