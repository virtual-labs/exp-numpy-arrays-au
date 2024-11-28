<h2>Theory</h2>
<u><h4>NumPy vs List:</h4></u>
<p><b>NumPy:</b> Optimized for numerical operations, uses contiguous memory, and supports multi-dimensional arrays. It’s faster and more memory-efficient than Python lists.</p>

<p><b>Python List:</b> Flexible and general-purpose, but slower for numerical tasks and lacks built-in support for advanced operations.</p>

<b>NumPy Array Creation:</b>

<li>np.array(): Create an array from a list.</li>
<b>Iteration in NumPy:</b>
<li>Basic iteration: Loop through array elements, but NumPy allows faster vectorized operations without loops.</li>
<li>np.nditer(): Efficiently iterate over multi-dimensional arrays.</li>

<b>Slicing in NumPy</b>
<p>Slicing in NumPy is a technique used to access a subset of elements from an array. It follows the syntax array[start:stop:step], and can be applied to both 1D and 2D arrays.</p>
<p>1D Array Slicing
In a 1D array, slicing allows you to extract a range of elements based on their indices.

Basic Slicing: You can specify the start and stop indices.</p>
<p>2D Array Slicing
Slicing in 2D arrays works similarly, but you must specify slicing for both rows and columns.</p>
<p>
<li>Start Index: Specifies where the slice starts (inclusive).</li>
<li>Stop Index: Specifies where the slice ends (exclusive)</li>.
<li>Step: Defines the interval between elements.</li>
<li>Negative Indexing: Allows you to count from the end of the array (e.g., -1 is the last element)</li></p>