<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NumPy World</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            padding: 20px;
            background-color: #f8f8f8;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #2c3e50;
        }
        pre {
            background-color: #ecf0f1;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
        code {
            font-family: "Courier New", Courier, monospace;
            background-color: #e7e9eb;
            padding: 2px 4px;
            border-radius: 3px;
        }
        ul {
            margin: 10px 0;
        }
    </style>
</head>
<body>

<h1>Welcome to NumPy World</h1>

<pre><code>import numpy as np
myarr = np.array([[1000, 2000, 3000, 4000]], np.int64)
print(myarr[0,1])  # Output: 2000
print(myarr.shape)  # Output: (1, 4)
print(myarr.dtype)  # Output: dtype('int64')
myarr[0, 1] = 66
print(myarr)  # Output: array([[1000,   66, 3000, 4000]])
</code></pre>

<h2>Array Creation Methods</h2>
<ol>
    <li><strong>Conversion from other Python structures:</strong>
        <pre><code>listarray = np.array([[1, 2, 3], [5, 8, 5], [0, 3, 1]])
print(listarray)  # Output: array([[1, 2, 3], [5, 8, 5], [0, 3, 1]])
</code></pre>
    </li>
    <li><strong>Intrinsic NumPy array creation objects:</strong>
        <pre><code>zeros = np.zeros((2, 5))
print(zeros)  # Output: array([[0., 0., 0., 0., 0.], [0., 0., 0., 0., 0.]])
</code></pre>
    </li>
</ol>

<h2>Basic Operations</h2>
<pre><code>ar = np.array([[1, 2, 3], [4, 5, 6], [7, 1, 0]])
print(ar.sum(axis=0))  # Output: array([12,  8,  9])
print(ar.sum(axis=1))  # Output: array([ 6, 15,  8])
</code></pre>

<h2>Numpy Axis</h2>
<pre><code>ar = np.array([[1, 2, 3], [4, 5, 6], [7, 1, 0]])
print(ar.argmax(axis=0))  # Output: array([2, 1, 1])
print(ar.argsort(axis=1))  # Output: array([[0, 1, 2], [0, 1, 2], [2, 1, 0]])
</code></pre>

<h2>Conclusion</h2>
<p>This README provides an overview of some basic functionalities of the NumPy library in Python. Explore the power of NumPy for numerical computing!</p>

</body>
</html>

