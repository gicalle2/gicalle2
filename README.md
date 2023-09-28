<h2> Hi, I'm Gicalle</h2>
<em>Currently working with Artificial Intelligence, Python</em>

```python
input_vector = np.array([1.66, 1.56])
weights_1 = np.array([1.45, -0.66])
bias = np.array([0.0])

def sigmoid(x):
    return 1 / (1 + np.exp(-x))

def predict(input_vector, weights, bias):
     layer_1 = np.dot(input_vector, weights) + bias
     layer_2 = sigmoid(layer_1)
     return layer_2

prediction = predict(input_vector, weights_1, bias)

print(f"The prediction result is: {prediction}")
```

---
