# Machine Learning with Scikit-Learn: Iris Flower Dataset

This project follows Jason Brownlee’s step-by-step guide on [Machine Learning in Python](https://machinelearningmastery.com/machine-learning-in-python-step-by-step/) using Scikit-Learn. It explores the classic [Iris flower dataset](https://en.wikipedia.org/wiki/Iris_flower_data_set), applying fundamental machine learning techniques.

## Project Overview

- Uses **Scikit-Learn** for machine learning
- Works with the **Iris dataset** for classification
- Follows a structured **step-by-step approach**
- Implements best practices for **dependency management** and **Git tracking**

---

## Getting Started

### 1️⃣ Install Dependencies

Before running the project, install required dependencies using:

```bash
pip install -r requirements.txt
```

If you're a new coder, "requirements.txt" will automatically install all the components you need to run this project.

### 2️⃣ Dependencies (requirements.txt)

This project requires:

```
scipy
numpy
matplotlib
pandas
scikit-learn
```

Of course, ensure you have Python installed before proceeding.

### 3️⃣ Run the Project
Execute the main script:

Terminal
```
python Iris.py
### (Replace your_script.py with the actual filename if you changed it.)
```

### 🛠 Git Best Practices
Ignoring Tracked Files Retroactively
If .gitignore isn’t working as expected, remove tracked files and reapply .gitignore:

Terminal
```
git rm -r --cached .
git add .
git commit -m "Reapply .gitignore rules"
git push origin main
```

.gitignore doesn’t retroactively remove tracked files.
git rm -r --cached . forces Git to reprocess ignored files.
Avoid "Discard All Changes" in VS Code when dealing with venv/—this can delete critical files instead of just untracking them.

### 📸 Project Snapshots


### 📚 References
[Machine Learning in Python](https://machinelearningmastery.com/machine-learning-in-python-step-by-step/)
[Jason Brownlee's Articles](https://machinelearningmastery.com/author/jasonb/)
[Iris flower dataset](https://en.wikipedia.org/wiki/Iris_flower_data_set)
