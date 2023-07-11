# Lego_Minifigures

## Model 1
```python
    self.conv1 = nn.Conv2d(3, 6, 5)
    self.pool = nn.MaxPool2d(2, 2)
    self.conv2 = nn.Conv2d(6, 16, 5)
    self.fc1 = nn.Linear(250000, 120)
    self.fc2 = nn.Linear(120, 84)
    self.fc3 = nn.Linear(84, 39)
```
28% Accuracy. Loss went to 0.00 around 32 epochs. 
Need a more complex NN.

## Model 2
```python
    self.conv1 = nn.Conv2d(3, 16, 5)
    self.pool = nn.MaxPool2d(2, 2)
    self.conv2 = nn.Conv2d(16, 32, 5)
    self.pool = nn.MaxPool2d(2, 2)
    self.conv3 = nn.Conv2d(32, 32, 5)
    self.fc1 = nn.Linear(500000, 120)
    self.fc2 = nn.Linear(120, 84)
    self.fc3 = nn.Linear(84, 39)
```
32% Accuracy
