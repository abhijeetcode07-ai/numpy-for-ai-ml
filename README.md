
# NumPy for AI/ML — Visual Master Notes

### A structured, beginner-friendly guide to understanding NumPy from the ground up.

![Python](https://img.shields.io/badge/Python-NumPy-3776AB?style=flat&logo=python&logoColor=white)
![Focus](https://img.shields.io/badge/Focus-AI%2FML%20Foundations-6A5ACD?style=flat)
![Learning](https://img.shields.io/badge/Style-Visual%20%26%20Practical-2E8B57?style=flat)

NumPy is one of the fundamental tools in the Python data science and machine learning ecosystem. However, learning it can be challenging when you have to choose between quick introductory tutorials and comprehensive textbooks that contain far more material than you may need at the beginning.

**This repository is my attempt to bridge that gap.**

I created these notes while learning NumPy for my AI/ML journey, drawing on the practical introduction offered by video tutorials and the depth of *Python Data Science Handbook* by Jake VanderPlas. The goal is to turn those learning experiences into a structured resource that explains the important concepts in depth without making them unnecessarily difficult to follow.

Rather than simply listing functions and their syntax, these notes focus on understanding how NumPy works, why particular operations matter, and how to apply them to real problems.

---

## 🎯 Why This Repository Exists

When learning NumPy, beginners often encounter two different challenges:

- **Quick tutorials:** They can provide a straightforward introduction, but learners may still need more detailed explanations, additional practice, and a deeper understanding of how the concepts connect to AI/ML.
- **Comprehensive textbooks:** They provide valuable depth and context, but navigating extensive material can make it difficult for beginners to decide what to learn first and what to prioritise.

I wanted a learning resource that combines the accessibility of a guided tutorial with the conceptual depth of a textbook.

That is the purpose of this repository: **to make NumPy deep enough to understand, structured enough to follow, and practical enough to use.**

## ✨ What Makes These Notes Different?

- **Concept-first explanations:** Understand the idea before diving into the syntax.
- **Visual learning:** Use diagrams, visual examples, and step-by-step illustrations to understand how array operations work.
- **Code with explanations:** Learn what each important line does instead of copying code without understanding it.
- **Expected outputs:** Compare your results with the outputs shown in the notes.
- **AI/ML relevance:** Connect NumPy concepts to tasks such as data preprocessing, numerical computation, normalisation, classification, and nearest-neighbour search.
- **Common mistakes and debugging:** Understand tricky behaviour, shape mismatches, data types, Boolean logic, and other common pitfalls.
- **Practice and revision:** Test your understanding with exercises, output-prediction questions, debugging problems, and answer keys where provided.
- **Prioritised learning:** Distinguish essential concepts from useful extras and functions you can look up when needed.

The objective is not to memorise every NumPy function. It is to understand the core concepts well enough to read, write, and debug numerical Python code confidently.

---

## 📚 What's Inside?

The repository is organised into four parts, following a progressive learning path.

### Part 01 — NumPy Fundamentals

**File:** `Numpy Part 01.pdf`

Build a foundation in NumPy arrays and understand how they differ from ordinary Python lists.

Topics include:

- Python objects, lists, and vectorisation fundamentals
- Creating arrays from lists and generating arrays
- NumPy data types (`dtype`) and memory considerations
- Array attributes: `shape`, `ndim`, `size`, `itemsize`, and `nbytes`
- Indexing and slicing one-dimensional and multidimensional arrays
- Views versus copies and the importance of `.copy()`
- Reshaping arrays and using `np.newaxis`
- Concatenating and splitting arrays

**Learning goal:** Understand how NumPy represents, organises, and manipulates numerical data.

### Part 02 — Computation and Aggregation

**File:** `Numpy Part 02.pdf`

Learn how NumPy performs numerical operations efficiently and how to extract useful information from arrays.

Topics include:

- Python loops versus vectorised computation
- Universal functions (ufuncs)
- Element-wise arithmetic and mathematical operations
- Absolute values and trigonometric functions
- Exponential and logarithmic functions
- Aggregations using `sum`, `min`, and `max`
- Understanding `axis` in multidimensional arrays
- Statistical operations such as `mean` and `std`
- Functions such as `argmax` and other array summaries

**Learning goal:** Become comfortable performing numerical computations and extracting information from datasets.

### Part 03 — Broadcasting, Comparisons, and Boolean Logic

**File:** `Numpy Part 03.pdf`

Understand how NumPy operates on arrays with different shapes and how to select data using conditions.

Topics include:

- Broadcasting and its three compatibility rules
- Working with `np.newaxis` and array shapes
- Understanding and fixing broadcasting errors
- Centring and scaling data
- Comparison operators and Boolean arrays
- Counting and checking conditions with `np.sum`, `np.mean`, `np.any`, and `np.all`
- Combining conditions using `&`, `|`, and `~`
- Boolean masks for filtering array elements
- Understanding the difference between `and` / `or` and `&` / `|`

**Learning goal:** Develop the shape intuition and conditional-selection skills needed for numerical computing and machine learning.

### Part 04 — Fancy Indexing, Sorting, and k-Nearest Neighbours

**File:** `Numpy Part 04.pdf`

Explore more advanced array-selection techniques and apply them to a simple machine-learning algorithm.

Topics include:

- Fancy indexing and selecting multiple positions
- Two-dimensional indexing and selecting rows or columns
- Combining indexing techniques
- Random selection and train/test splitting
- Modifying selected elements and `np.add.at`
- Binning data with `searchsorted`
- Sorting arrays using `np.sort` and `.sort()`
- Understanding `np.argsort`, `np.partition`, and `np.argpartition`
- Building k-nearest neighbours (KNN) step by step
- Understanding Big-O notation and how computational work grows with data size

**Learning goal:** Use NumPy indexing and sorting techniques to solve practical problems and understand the numerical foundations of a simple machine-learning algorithm.

---

## 🗺️ Recommended Learning Path

If you are new to NumPy, follow the parts in order:

1. **Part 01:** Understand arrays, shapes, data types, and indexing.
2. **Part 02:** Learn vectorisation, mathematical operations, and aggregations.
3. **Part 03:** Master broadcasting, Boolean masks, and conditional selection.
4. **Part 04:** Practise fancy indexing, sorting, and the KNN example.

Do not rush through the material. The aim is to build an understanding of each concept before moving to the next.

## 💻 How to Use These Notes

You can study the PDFs on their own, but you will benefit much more by running the examples yourself.

1. Open [Google Colab](https://colab.research.google.com/) or use a local Python environment.
2. Install NumPy if it is not already available:

   ```bash
   pip install numpy
   ```

3. Open a topic in the corresponding PDF.
4. Type the example into your notebook instead of only reading it.
5. Predict the output before running the code.
6. Change one value, shape, or argument at a time and observe what happens.
7. Attempt the practice questions before checking the answer key.

The notes were prepared using NumPy 2.x, with NumPy 2.4.4 specified in several parts. Minor differences in outputs or behaviour may occur with different library versions or execution environments.

**A useful rule:** If you cannot explain what a line of NumPy code does in plain language, revisit the concept before memorising the syntax.

---

## 🔗 Learning Resources and Acknowledgements

These notes were developed through my learning process using the following resources. Both are valuable learning materials, and I encourage readers to explore the original sources alongside this repository.

### 1. Python Data Science Handbook — Jake VanderPlas

**Official book website:**  
https://jakevdp.github.io/PythonDataScienceHandbook/

The *Python Data Science Handbook* by Jake VanderPlas is the primary conceptual reference for these notes, particularly Chapter 2, which covers the fundamentals of NumPy arrays and computation.

I used the relevant sections as a foundation for my study, then organised the material into a slower, more guided learning experience with visual explanations, worked examples, code outputs, AI/ML connections, and practice questions where included.

The intention is to make selected concepts easier to study progressively, not to replace the original book. Readers looking for the broader theoretical context and the author's complete treatment should consult the handbook itself.

**Acknowledgement:** Full credit to Jake VanderPlas for the original handbook and the educational work that informed my learning.

### 2. NumPy Tutorial — Keith Galli / freeCodeCamp

**Watch the tutorial on YouTube:**  
https://youtu.be/QUT1VHiLmmI?si=GlJvyLPbnwvzHNFb

This tutorial provides a practical introduction to NumPy and is useful for getting familiar with its syntax and common operations.

I used the video-tutorial learning approach as another reference point while developing these notes. The PDFs go further into selected concepts with more detailed explanations, visual reasoning, practice material, and connections to AI/ML.

The two resources serve different purposes: the video is a convenient introduction, while the handbook provides broader depth. These notes are my attempt to create a guided path between those learning experiences.

**Acknowledgement:** Credit to Keith Galli for the tutorial and to freeCodeCamp for making educational programming content accessible.

*This is an independent learning project. It is not an official NumPy, freeCodeCamp, or Jake VanderPlas publication, and it is not affiliated with or endorsed by those authors or organisations.*

---

## 👨‍💻 About the Author

Hi, I'm Abhijeet, a BCA student building my foundations in computer science, Python, data science, and AI/ML.

I created these notes as part of my own learning journey because I wanted to understand NumPy beyond memorising function syntax. I hope they help other learners develop the same conceptual clarity and confidence.

If you find this repository useful, feel free to explore the notes, practise the examples, and share the repository with other learners.

### Connect with me on LinkedIn

[![LinkedIn — Follow me](https://img.shields.io/badge/LinkedIn-Follow%20me-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhijeet-upadhyaya-20018a409/)

---

## 🤝 Feedback and Contributions

If you find an error, have a suggestion, or think an explanation could be clearer, feedback is welcome.

You can open an issue to report a mistake, suggest an improvement, or discuss a topic that could benefit from a clearer explanation.

The goal is to keep learning practical, understandable, and accessible to people who are building their AI/ML foundations.

---

## ⭐ If This Repository Helps You

If these notes help you understand NumPy better, consider giving the repository a **star** on GitHub. It helps other learners discover the resource.

Happy learning, and keep building your foundations in AI/ML!

