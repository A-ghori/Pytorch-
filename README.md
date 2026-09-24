# Pytorch-

## CPU vs GPU

```text
                 COMPUTER
                    │
          ┌─────────┴─────────┐
          ↓                   ↓
         CPU                 GPU
          │                   │
   General-purpose      Highly parallel
      processing        numerical work
          │                   │
   ┌──────┴──────┐      ┌─────┴──────────┐
   │             │      │                │
Data loading   Python  Tensor math    Matrix math
Preprocessing  Logic   Neural networks  Training
OS operations
          │                   │
          └─────────┬─────────┘
                    ↓
                  Result
```
GPU IS LIKE CALCULATION MACHINE IT BASICALLY CALCULATE THE COMPLEX NUMERICAL PROBLEMS AND CPU IS FOR CALCULATING
