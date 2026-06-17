# ml

## Purpose
Native Machine Learning framework for SageLang, leveraging hardware acceleration (NPU/GPU).

## Features
- **Tensors**: Core tensor data structure and operations.
- **Neural Networks**: Layers, models, and training loops.
- **Optimizers**: SGD, Adam, and others.
- **Visualization**: Tools for monitoring training progress.

## Usage Example
```sage
import ml.tensor
import ml.nn

let t = tensor.ones([10, 10])
let model = nn.Sequential([nn.Linear(10, 5), nn.ReLU()])
```
