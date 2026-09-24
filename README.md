# Pytorch-

## CPU VS GPU
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
