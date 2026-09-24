# Pytorch-

## CPU VS GPU
lower code follow this flow

x
↓
CPU memory
↓
PyTorch operation
↓
CPU calculates

## CPU is a general-purpose processor, while GPU is specialized for highly parallel workloads, especially large-scale numerical/tensor operations.

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
