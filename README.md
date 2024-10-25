<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NumPy Tutorial</title>
</head>
<body>
    <h1>NumPy Tutorial 🐍</h1>
    <p>Welcome to the NumPy Tutorial! This repository is designed to help you understand the fundamentals of NumPy, a powerful library for numerical computing in Python. Whether you're a beginner or looking to refresh your skills, this tutorial covers essential topics to get you started.</p>

    <h2>Table of Contents 📚</h2>
    <ol>
        <li><a href="#introduction-to-numpy">Introduction to NumPy</a></li>
        <li><a href="#creating-numpy-arrays">Creating NumPy Arrays</a>
            <ul>
                <li><a href="#1-conversion-from-other-python-structures">1. Conversion from Other Python Structures</a></li>
                <li><a href="#2-intrinsic-numpy-array-creation-methods">2. Intrinsic NumPy Array Creation Methods</a></li>
            </ul>
        </li>
        <li><a href="#understanding-array-properties">Understanding Array Properties</a>
            <ul>
                <li><a href="#shape">Shape</a></li>
                <li><a href="#data-type-dtype">Data Type (dtype)</a></li>
            </ul>
        </li>
        <li><a href="#numpy-axes">NumPy Axes</a></li>
        <li><a href="#conclusion">Conclusion</a></li>
    </ol>

    <h2 id="introduction-to-numpy">Introduction to NumPy</h2>
    <p>NumPy is a fundamental package for scientific computing in Python. It provides support for arrays, matrices, and a large library of mathematical functions to operate on these data structures.</p>

    <h2 id="creating-numpy-arrays">Creating NumPy Arrays</h2>

    <h3 id="1-conversion-from-other-python-structures">1. Conversion from Other Python Structures</h3>
    <p>You can create a NumPy array by converting other Python data structures, such as lists or tuples. For example:</p>
    <pre><code>import numpy as np

# Convert a list to a NumPy array
list_data = [1, 2, 3, 4, 5]
array_from_list = np.array(list_data)
print(array_from_list)</code></pre>

    <h3 id="2-intrinsic-numpy-array-creation-methods">2. Intrinsic NumPy Array Creation Methods</h3>
    <p>NumPy provides several intrinsic methods to create arrays directly:</p>
    <ul>
        <li><code>np.zeros()</code>: Creates an array filled with zeros.</li>
        <li><code>np.ones()</code>: Creates an array filled with ones.</li>
        <li><code>np.arange()</code>: Creates an array with a range of values.</li>
        <li><code>np.linspace()</code>: Creates an array with evenly spaced values.</li>
    </ul>
    <p>Example:</p>
    <pre><code># Create an array of zeros
zeros_array = np.zeros((2, 3))
print(zeros_array)</code></pre>

    <h2 id="understanding-array-properties">Understanding Array Properties</h2>

    <h3 id="shape">Shape</h3>
    <p>The shape of a NumPy array represents the dimensions of the array. You can access the shape attribute using:</p>
    <pre><code>array_shape = array_from_list.shape
print(array_shape)</code></pre>

    <h3 id="data-type-dtype">Data Type (dtype)</h3>
    <p>NumPy arrays have a specific data type that defines the type of elements in the array. You can check the data type using:</p>
    <pre><code>array_dtype = array_from_list.dtype
print(array_dtype)</code></pre>

    <h2 id="numpy-axes">NumPy Axes</h2>
    <p>Understanding axes in NumPy is crucial for manipulating data. An array's axes are the dimensions along which operations can be performed. For instance, in a 2D array:</p>
    <ul>
        <li>Axis 0 refers to the rows.</li>
        <li>Axis 1 refers to the columns.</li>
    </ul>
    <p>Example:</p>
    <pre><code># Creating a 2D array
two_d_array = np.array([[1, 2, 3], [4, 5, 6]])
print("Array:", two_d_array)
print("Sum along axis 0:", np.sum(two_d_array, axis=0))  # Sum of each column</code></pre>

    <h2 id="conclusion">Conclusion</h2>
    <p>This tutorial provided an overview of essential NumPy functionalities, including array creation, properties, and axes. NumPy is a versatile library that serves as a foundation for many scientific computing tasks in Python.</p>
    <p>Feel free to explore the code examples provided in this repository and experiment with different NumPy functionalities. Happy coding! 🚀</p>

    <h2>License</h2>
    <p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>
</body>
</html>
