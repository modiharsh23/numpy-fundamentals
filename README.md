# NumPy Fundamentals: A Practical Guide 🚀

Welcome to the NumPy Fundamentals repository! This collection of Jupyter notebooks is designed to provide a hands-on introduction to the core concepts of the NumPy library, an essential tool for numerical computing in Python.

Whether you're new to data science or looking for a quick refresher, these notebooks will guide you through creating, manipulating, and performing operations on NumPy arrays.

---

### 📚 Notebooks Overview

This repository is structured into five key notebooks, each focusing on a different aspect of NumPy.

**1. `01_core_fundamentals.ipynb`**
   - **Array Creation**: Learn to create 1D, 2D, and 3D arrays.
   - **Built-in Functions**: Explore functions like `np.arange()`, `np.zeros()`, `np.ones()`, and `np.linspace()`.
   - **Random Number Generation**: Generate arrays with random data from uniform and normal distributions.
   - **Array Attributes**: Understand key attributes like `.shape`, `.size`, `.ndim`, and `.dtype`.

**2. `02_indexing_and_slicing.ipynb`**
   - **Basic Indexing**: Access individual elements in 1D and 2D arrays.
   - **Slicing**: Extract subarrays and sub-matrices.
   - **Conditional Selection**: Use boolean masking to filter array elements based on conditions.
   - **Views vs. Copies**: Understand the important difference between a view and a copy (`.copy()`) to avoid unintentional data modification.

**3. `03_array_manipulation.ipynb`**
   - **Reshaping**: Change the shape of an array with `.reshape()`.
   - **Transposing**: Swap axes using the `.T` attribute.
   - **Flattening**: Convert multi-dimensional arrays into a single dimension using `.flatten()` and `.ravel()`.
   - **Combining Arrays**: Concatenate and stack arrays vertically (`vstack`) and horizontally (`hstack`).

**4. `04_mathematical_operations.ipynb`**
   - **Vectorized Operations**: Perform fast, element-wise arithmetic.
   - **Universal Functions (ufuncs)**: Apply mathematical functions like `np.sqrt()` and `np.exp()`.
   - **Aggregation**: Compute statistical metrics like sum, mean, and standard deviation.
   - **Axis-based Operations**: Perform aggregations along specific axes (rows or columns).
   - **`argmax` & `argmin`**: Find the indices of maximum and minimum values.

**5. `05_broadcasting_and_linear_algebra.ipynb`**
   - **Broadcasting**: Learn how NumPy handles operations on arrays of different but compatible shapes.
   - **Linear Algebra**:
     - Differentiate between element-wise (`*`) and matrix multiplication (`@`).
     - Use the `np.linalg` submodule to compute the inverse, determinant, and eigenvalues of a matrix.

---

### 💻 How to Use

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/numpy-fundamentals.git](https://github.com/your-username/numpy-fundamentals.git)
    ```
2.  **Navigate to the directory:**
    ```bash
    cd numpy-fundamentals
    ```
3.  **Open the notebooks** in Jupyter Lab, Jupyter Notebook, or VS Code to explore the code and explanations.

Happy coding! ✨