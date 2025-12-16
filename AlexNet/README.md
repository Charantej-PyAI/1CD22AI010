1. AlexNet Improvements

Previous Problems

No GPU support
Missing normalization
No data augmentation
No checkpoint saving
No separation of training vs inference

What Is Improved

Added GPU acceleration with model.to(device)
Added data augmentation (RandomCrop, Flip, ColorJitter)
Added cross-entropy + Adam optimizer
Added learning rate scheduler
Added model checkpoints
Added accuracy function
Added torchvision.datasets.ImageFolder structure support
