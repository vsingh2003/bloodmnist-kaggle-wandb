# BloodMNIST Experiment Tracking with Weights & Biases

## Overview
This project demonstrates experiment tracking and monitoring for an image classification task using Weights & Biases (W&B). The model was trained on the BloodMNIST dataset in Google Colab using PyTorch and submitted to a Kaggle competition.

This repository is part of my technical portfolio and fulfills the **Experiment Tracking / Monitoring** requirement in my course portfolio.

## Project Goal
The goal of this project was to train an image classification model, track the training process using W&B, generate a Kaggle submission file, and document the workflow in a report that shows metrics, progress, and results.

## Tools and Technologies
- Python
- Google Colab
- PyTorch
- timm
- Weights & Biases (W&B)
- Kaggle

## Workflow
1. Installed and imported the required libraries in Google Colab.
2. Logged into Weights & Biases and initialized a project run.
3. Downloaded the dataset from W&B Artifacts.
4. Prepared training, validation, and test datasets.
5. Trained the model while logging training and validation metrics.
6. Generated predictions on the test set.
7. Saved the predictions as `submission.csv`.
8. Submitted the predictions to the Kaggle leaderboard.
9. Created a W&B report to summarize the experiment.

## Model Details
- Model: `mobilenetv4_hybrid_large.e600_r384_in1k`
- Epochs: `5`
- Batch size: `128`
- Learning rate: `0.001`

## Results
- Kaggle Public Score: `0.72660`
- Kaggle Private Score: `0.71392`

The project successfully produced a valid Kaggle submission and tracked the experiment through W&B charts, dataset previews, logged artifacts, and a final report.

## My Role
I completed the project workflow in Google Colab, configured W&B tracking, ran the notebook, generated the submission file, submitted it to Kaggle, and organized the outputs into a portfolio-ready GitHub repository.

## Key Skills Demonstrated
- Experiment tracking and monitoring
- Training and validation metric logging
- Artifact logging
- Model evaluation workflow
- Kaggle competition submission
- Technical documentation

## Reflection
This project helped me understand how experiment tracking supports machine learning workflows beyond just training a model. By using Weights & Biases, I was able to log metrics, compare progress, and keep records of important outputs such as the submission file and trained model artifacts.

One of the most useful lessons from this project was learning how to connect technical work with documentation and reporting. Instead of only producing a notebook, I also created a W&B report and organized the work into a GitHub portfolio project. This made the project more professional and more suitable for academic and career use.

If I improve this project in the future, I would test multiple model architectures, compare runs more clearly in W&B, and add reproducibility files such as `requirements.txt` and a cleaner folder structure.

## Repository Contents
- `W-B_and_Norquest.ipynb` — original notebook used for training and submission
- Kaggle screenshot — proof of leaderboard submission
- W&B screenshot/report — proof of experiment tracking
- `README.md` — project summary and reflection

## Portfolio Relevance
This project supports my goal of building a portfolio for machine learning, data science, and MLOps-related roles. It shows that I can not only train a model, but also track experiments, document results, and present technical work in a professional format.
