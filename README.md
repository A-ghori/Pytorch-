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

                 COMPUTER
                    │
          ┌─────────┴─────────┐
          ↓                   ↓
         CPU                 GPU
          │                   │
   data loading          tensor math
   Python code           matrix math
   control logic         neural network
   preprocessing         training
          │                   │
          └─────────┬─────────┘
                    ↓
                 Result
