# Heap Implementation in Python

This repository contains a simple implementation of a **Max Heap** data structure in Python. The implementation is provided in a Jupyter Notebook.

## Features

* `insert(e)` → Insert an element into the heap.
* `top()` → Retrieve the maximum element without removing it.
* `delete()` → Remove and return the maximum element.
* `heapSort(list1)` → Perform heap sort on a given list.
* `EmptyHeapException` → Custom exception for empty heap operations.

## Example Usage

```python
from Heap import Heap

list1 = [34, 56, 12, 78, 43, 25, 10, 80, 60]
h = Heap()
sorted_list = h.heapSort(list1)
print(sorted_list)  # Output: [10, 12, 25, 34, 43, 56, 60, 78, 80]
```

## Requirements

* Python 3.x
* Jupyter Notebook (if you want to run the `.ipynb` file)

Install Jupyter with:

```bash
pip install notebook
```

## Running the Notebook

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/heap-python.git
   cd heap-python
   ```
2. Open Jupyter Notebook:

   ```bash
   jupyter notebook Heap.ipynb
   ```

## Future Improvements

* Add support for **Min Heap**.
* Optimize heap operations.
* Provide visualization of heap structure.
