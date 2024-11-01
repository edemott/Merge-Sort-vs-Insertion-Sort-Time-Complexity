## Merge Sort vs Insertion Sort Performance Analysis

This project compares the time complexity and performance of two popular sorting algorithms: Merge Sort and Insertion Sort. The report investigates the efficiency of these algorithms across different input sizes and identifies the approximate point where Merge Sort becomes more efficient than Insertion Sort.

Project Overview

Sorting is a fundamental operation in computer science, and choosing an efficient algorithm is crucial when working with large datasets. Merge Sort is generally preferred for its O(n log n) time complexity, while Insertion Sort performs at O(n^2). However, Insertion Sort can be more efficient on smaller datasets due to its low overhead. This analysis helps visualize where Merge Sort overtakes Insertion Sort in terms of performance as input size increases.

Key Findings

	•	Merge Sort shows consistently lower time complexity as the dataset size grows, due to its O(n log n) performance.
	•	Insertion Sort performs well for small datasets, but its O(n^2) time complexity makes it slower as the number of elements increases.
	•	The crossover point, where Merge Sort becomes faster than Insertion Sort, occurs at approximately n = 60 elements, as indicated in the plot.

Plot

The plot above illustrates the performance of both algorithms as the number of elements (n) increases. The vertical dashed line represents the crossover point at approximately n = 60 elements.

How to Use This Repository

	1.	Clone the repository: Clone this project to your local machine.

git clone https://github.com/edemott/Merge-Sort-vs-Insertion-Sort-Time-Complexity


	2.	Install dependencies: Make sure you have the required libraries installed. This project relies on Python and the Matplotlib library for plotting.

pip install matplotlib


	3.	Run the code: The main script runs both Merge Sort and Insertion Sort on various dataset sizes, records their execution time, and plots the results.

Project Files

	•	Analysis.ipynb: Contains the code to perform the sorting and timing of Merge Sort and Insertion Sort, along with plotting functions.
	•	README.md: This README file, summarizing the purpose and findings of the project.

Conclusion

This analysis reinforces the theoretical expectations of sorting time complexities and provides practical insight into the efficiency of Merge Sort and Insertion Sort across different dataset sizes. For small arrays, Insertion Sort is efficient, but for larger datasets, Merge Sort is the preferred choice due to its scalability.

License

This project is open source and available under the MIT License.

This README should serve as a useful overview for anyone interested in understanding the project and its findings.
