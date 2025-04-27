# Dask Benchmark Project
📚 About
This project explores and benchmarks Dask, a powerful parallel computing library for Python, against Pandas when processing large-scale datasets.

Through practical experimentation, we highlight Dask's ability to handle data that exceeds available RAM and its advantages in distributed and parallel execution.

The project was developed as part of a research assignment by:

Nguyễn Phạm Việt Quang - 22028134

Phạm Tiến Sơn - 22024531

🚀 Project Structure

File	Description
main.ipynb	Jupyter Notebook containing benchmarking code between Pandas and Dask.
Group7_Dask_Presentation.pptx	Final presentation slides summarizing the project, Dask features, and benchmark results.
.gitignore	Standard Git ignore settings.
.vscode/	VS Code project settings.
🛠️ Key Technologies
Python 3.8+

Dask

Pandas

NumPy

Jupyter Notebook

📈 Experiment Setup
Dataset Size: ~10GB simulated sales data

Hardware: Local machine with limited RAM (~8GB)

Task: Calculate average revenue across the dataset.

Goal: Compare execution time and memory usage between Pandas and Dask.

🔥 Benchmark Highlights
Pandas struggles with MemoryError or becomes extremely slow when dataset size exceeds RAM capacity.

Dask efficiently handles out-of-core computation, chunking data into partitions and computing results in parallel, significantly improving speed and memory efficiency.


Framework	Performance Summary
Pandas	Fast on small datasets, but limited by RAM for larger datasets.
Dask	Scales to datasets larger than memory by chunking and parallel processing.
