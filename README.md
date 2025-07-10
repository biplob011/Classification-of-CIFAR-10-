┌────────────────────┐
│   Start Project    │
└────────┬───────────┘
         ↓
┌────────────────────┐
│ Load CIFAR-10 Data │
└────────┬───────────┘
         ↓
┌────────────────────────────────────────┐
│ Preprocess Data                        │
│ - Normalize Images                     │
│ - One-Hot Encode Labels                │
│ - Apply Data Augmentation (optional)  │
└────────┬───────────────────────────────┘
         ↓
┌───────────────────────────────┐
│ Design CNN Architecture       │
│ - Conv + ReLU + Pool layers   │
│ - Dropout / Batch Norm        │
│ - Dense + Softmax layer       │
└────────┬──────────────────────┘
         ↓
┌───────────────────────────────┐
│ Train Model                   │
│ - Split Train/Validation Set │
│ - Use Optimizer (Adam/SGD)   │
│ - Categorical Cross-Entropy  │
└────────┬──────────────────────┘
         ↓
┌────────────────────────────────────┐
│ Evaluate Model Performance         │
│ - Test on Test Set                 │
│ - Accuracy, Precision, Recall, F1 │
│ - Confusion Matrix                │
└────────┬───────────────────────────┘
         ↓
┌────────────────────────────────────────┐
│ Optimize Model                         │
│ - Tune Hyperparameters (LR, batch)     │
│ - Use Early Stopping, Regularization   │
└────────┬───────────────────────────────┘
         ↓
┌──────────────────────┐
│ Compare With Baseline│
│ and Other Models     │
└────────┬─────────────┘
         ↓
┌──────────────────┐
│   End Project    │
└──────────────────┘
