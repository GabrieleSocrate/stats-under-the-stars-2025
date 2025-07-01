# Stats Under the Stars 2025 – Money Laundering Detection

This repository contains our solution to the *Stats Under the Stars 2025* hackathon, organized by the Italian Statistical Society.

The challenge was to detect suspicious transactions using a real-world financial dataset. We developed a binary classification model using R with engineered features such as repeated transactions and account similarity.

## Results
- 1st place on the public leaderboard
- 3rd place after final private evaluation

## Repository Structure

- `best-model.R`: Main script that performs feature engineering, trains a probit model, and generates predictions
- `dataset/`: Contains `train.csv` and `test.csv`
- `submission.txt`: Output file with predicted probabilities and binary labels

## How to Run

1. Place `train.csv` and `test.csv` inside the `dataset/` folder
2. Open and run `best-model.R` in R or RStudio
3. The script will generate `submission.txt`

## Team
-Gabriele Socrate
- Lorenzo Galli
- Georgii Kutivadze
- Matteo Moltrasio

## Links
- [Competition page on DataChallenge.it](https://www.datachallenge.it/)
