# An-Exploratory-Data-Analysis
This project analyzes employee turnover using a dataset of 14,999 records with 10 attributes, including satisfaction level, workload, tenure, promotions, and salary. By examining binary, categorical, and numerical data, it identifies key factors influencing attrition and retentio


Introduction
In this project, we investigated Python's potential for conducting data analysis, contrasting a basic Python implementation with more specialized libraries such as Pandas and NumPy. This experience offered important perspectives on the balance between simplicity, efficiency, and usability in data analysis processes.
Key Learnings
1.Grasping the Dataset  
•	Dealing with a dataset such as online_shoppers_intention.csv, which includes both numerical and categorical variables, necessitated careful management of the various data types. Employing descriptive statistics like standard deviation, median, mean and variance offered greater insight into the distribution and variability of the data.  
•	For categorical variables, calculating relative frequencies was crucial to examine trends and proportions.  
2.Pure Python Implementation  
•	Developing summary statistics using pure Python deepened my grasp of data manipulation. Utilizing essential constructs such as loops, lists, and dictionaries to compute metrics provided a clear insight into the workings of these operations at a fundamental level.  
Strengths
•	Portability: The code was independent of any external libraries, which made it very flexible for use on systems without additional dependencies.  
Challenges  
•	Performance: The pure Python approach was considerably slower with larger datasets, primarily due to its dependence on iterative calculations instead of vectorized operations.  
•	Complexity: Creating pure Python code for intricate functions like variance and interquartile range demanded greater effort and was more susceptible to errors than methods utilizing libraries.
3. Utilizing Pandas and NumPy  
•	Pandas and NumPy significantly streamlined the extraction of summary statistics. Functions such as .mean(), .median(), and .std() offered optimized solutions for numerical calculations, while .value_counts() managed categorical data with ease.  
Advantages
•	Efficiency: The vectorized computations in Pandas and NumPy considerably lowered execution times, as shown by our performance tests on both the original and expanded datasets.  
•	Scalability: These libraries are designed to handle extensive datasets effectively, making them ideal for practical applications..  
Difficulties
•	Dependency: Utilizing Pandas and NumPy necessitates the installation of additional libraries, which may not always be practical in limited environments.  
•	 Learning Curve: New users might initially find the syntax and features somewhat daunting.
4. Performance Comparison  
•	The project revealed the performance disparity between pure Python and solutions that leverage libraries. Although pure Python performed reasonably well with small datasets, the combination of Pandas and NumPy proved to be considerably faster when dealing with larger datasets.  
6. Real-World Relevance  
•	This exercise underscored the necessity of finding a balance between performance and simplicity in practical data analysis. While pure Python may be adequate for educational purposes or small-scale tasks, Pandas and NumPy are essential for professional data analysis owing to their speed, reliability, and comprehensive features.

Explore the utility of using ChatGTP to complete task 1
Breaking Down the Problem
The task requires calculating typical summary statistics, which generally include:
•	Count: The number of data points.
•	Sum: The total sum of the data.
•	Mean: The average value of the data.
•	Minimum and Maximum: The smallest and largest values in the data.
•	Median: The middle value in sorted data.
•	Standard Deviation: A measure of data spread.
2. Coding Steps
1.	Input Handling: Start with a list of numerical data (e.g., [3, 7, 8, 10, 2]).
2.	Define Helper Functions: Use loops and basic arithmetic to:
o	Calculate count, sum, mean.
o	Find minimum and maximum values using comparison operators.
o	Sort the data for median calculation.
o	Use the mean and calculate deviations for standard deviation.
3.	Organize Output: Display the statistics in a clear format
•	Understanding Requirements: Clarify ambiguities in the task, like which statistics to include or constraints.
•	Code Guidance: Suggest solutions based on pure Python constructs while adhering to restrictions.
•	Debugging Support: Analyze errors in your code and suggest corrections.
•	Educational Insights: Provide explanations for concepts like median or standard deviation, making sure your understanding aligns with course material.
5. Limitations of Using ChatGPT
•	Adherence to Restrictions: ChatGPT might sometimes suggest more advanced features (e.g., comprehensions). You need to confirm the solution aligns with course guidelines.
•	Learning Opportunity: Overreliance on ChatGPT might limit personal growth in cod
Reflection
This task highlighted the adaptability of Python in the realm of data analysis, providing both ease of use through its built-in functionalities and robust abstraction through specialized libraries. It also stressed the importance of a systematic method for data analysis, which includes preprocessing, computation, and result interpretation. By leveraging the advantages of pure Python for a solid foundational understanding, alongside the practicality offered by Pandas and NumPy, we acquired a comprehensive view on utilizing Python to tackle analytical challenges.



