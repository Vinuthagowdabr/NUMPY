🧮 NumPy Calculator 


An interactive, menu-driven NumPy Calculator built in Python that demonstrates arithmetic operations, statistical analysis, and array manipulation — all using the power of NumPy.
This project helps learners understand how NumPy simplifies mathematical computations on both 1D and 2D arrays through a user-friendly interface.

🎯 Project Overview

This project serves as a practical introduction to NumPy operations using an object-oriented and menu-driven Python program.
It covers essential array concepts like:

Arithmetic and statistical operations

Array reshaping, sorting, and filtering

It’s a perfect beginner-friendly project to strengthen your understanding of Python + NumPy.

✨ Features

🔹 Arithmetic Operations

Addition, subtraction, multiplication, division, and power

Safe division using NumPy’s divide() method to avoid zero-division errors

Supports both 1D and 2D arrays


🔹 Statistical Operations

Mean, median, standard deviation, and variance

Find minimum, maximum, sum, and product

Retrieve array shape, size, and data type


🔹 Array Manipulation

Reshape arrays safely using error handling

Sort arrays (ascending and descending)

Extract unique values

Access first and last elements

Filter elements greater than the mean

🚀 Getting Started
🧩 Prerequisites

Make sure you have the following installed:

Python 3.8+
NumPy library

💻 Installation

Clone the repository:

git clone https://github.com/yourusername/numpy-calculator.git
cd numpy-calculator


Install dependencies:

pip install numpy


Run the program:

python numpy_calculator.py

🧠 How It Works

When you run the program, you’ll see a menu like this:

======= NumPy Calculator =======
1. Arithmetic Operations
2. Statistical Operations
3. Array Manipulation
4. Exit


Choose an option, enter your array elements (1D or 2D), and see instant results!
All user inputs are handled safely using try-except blocks and loops to ensure smooth execution.

🧾 Example Output
➤ Arithmetic Example
Enter first array: 1 2 3
Enter second array: 4 5 6

Addition: [5. 7. 9.]
Subtraction: [-3. -3. -3.]
Multiplication: [ 4. 10. 18.]
Division: [0.25 0.4  0.5 ]
Power: [  1.  32. 729.]

➤ Statistical Example
Enter array: 10 20 30 40 50

Mean: 30.0
Median: 30.0
Standard Deviation: 14.14
Variance: 200.0
Minimum: 10.0
Maximum: 50.0
Sum: 150.0
Product: 12000000.0
Shape: (5,)
Size: 5
Data Type: float64

➤ Array Manipulation Example
Enter number of rows: 2
Enter number of columns: 3
Enter 6 elements: 1 2 3 4 5 6

Original Array:
 [[1. 2. 3.]
  [4. 5. 6.]]
Sorted: [1. 2. 3. 4. 5. 6.]
Unique Values: [1. 2. 3. 4. 5. 6.]
First Element: 1.0
Last Element: 6.0
Values Greater than Mean: [4. 5. 6.]

📖 Learning Objectives

After completing this project, you’ll learn:

How to perform vectorized arithmetic using NumPy arrays

How to apply statistical functions efficiently

How to reshape and manipulate multidimensional data

How to implement error handling and loops in interactive programs

🔧 Key NumPy Functions Used
Category	Functions
Arithmetic	add(), subtract(), multiply(), divide(), power()
Statistics	mean(), median(), std(), var(), min(), max(), sum(), prod()
Shape & Info	shape, size, dtype, reshape()
Manipulation	sort(), unique(), flatten()


📂 Project Structure

numpy-calculator/

│

├── numpy_calculator.py     # Main Python file

├── README.md               # Project documentation

└── LICENSE                 # License file (optional)

🎓 Educational Use

This project is ideal for:

Students learning NumPy fundamentals

Beginners practicing Python OOP concepts

Lab assignments or coding exercises

Demonstrating array operations in interviews

🤝 Contributing

Contributions are always welcome!
You can:

Add visualization features using matplotlib

Extend calculator to support 3D arrays

Improve error messages or user prompts

Steps to Contribute:

Fork the repository

Create a feature branch (git checkout -b feature/Improvement)

Commit your changes (git commit -m "Enhanced array manipulation")

Push to the branch (git push origin feature/Improvement)

Create a Pull Request

📝 License

This project is licensed under the MIT License — see the LICENSE file for details.

👨‍💻 Author

Vinutha B R

GitHub:https://github.com/Vinuthagowdabr

Email: vinuthabr7676@gmail.com

🙏 Acknowledgments

NumPy Official Documentation

Python.org

Jupyter Project
 for interactive learning

All open-source contributors who make learning easier

⭐ If you found this project helpful, don’t forget to star the repository!

Happy Coding with NumPy! 💻✨

