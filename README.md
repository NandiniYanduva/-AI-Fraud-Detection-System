# AI-Based Bank Fraud Detection System

## Overview
An end-to-end machine learning system
that detects fraudulent bank transactions
in real time using XGBoost and Groq AI.

## Dataset
- 51,000 bank transactions
- 12 features
- 4.92% fraud rate

## Models Compared
| Model | Recall |
|-------|--------|
| Logistic Regression | 55% |
| Random Forest | 3% |
| XGBoost | 91.77% |
| Stacking Ensemble | 34% |

## Best Model: XGBoost
- Recall: 91.77%
- Threshold: 0.10
- scale_pos_weight: 19.32

## Risk Scoring System
| Risk Level | Probability | Action |
|-----------|-------------|--------|
| Low | 0-30% | Auto Approve |
| Medium | 31-60% | Send OTP |
| High | 61-80% | OTP + Security Question |
| Critical | 81-100% | Block + Full Verification |

## GenAI Integration
Groq AI (Llama 3.3-70B) generates
customer friendly fraud alert messages

## Technologies
Python, XGBoost, Scikit-Learn,
Pandas, NumPy, Groq AI, Jupyter Notebook

## Project Structure
- training.ipynb - Phase 1 Model Training
- prediction.ipynb - Phase 2 Prediction

## Author
Yanduva Nandini
MSc Computer Science
University of East London
