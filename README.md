Startup Success Predictor

This project uses a PyTorch neural network to predict the outcome of startups (acquired, operating, closed, IPO) based on funding data from the `investments_VC.csv` dataset.

Dataset
- The dataset (`investments_VC.csv`) is sourced from Kaggle: [Startup Investments (Crunchbase)](https://www.kaggle.com/datasets/justinas/startup-investments).
- It contains information about startups, including total funding, number of funding rounds, founding year, and status.

 Files
- `train.py`: The script to train the model.
- `startup_predictor.pth`: The trained PyTorch model weights.
- `scaler.pkl`: The scaler used to preprocess the features.
- `requirements.txt`: List of dependencies.

 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/100hard/KaggleStartupSuccessPredictor.git
   cd KaggleStartupSuccessPredictor
