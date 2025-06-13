# 🧪 Python Lab Tutorials for Undergraduate Physics

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/yourusername/python-lab-tutorials/HEAD)

> Are you new in the lab? Not sure where to start with data analysis in the optics lab?  
> **I’ve been there.** So I tried to give you some answers!

This is a student-friendly, optics-skewed Python toolbox designed to help you go from "what am I even looking at?" to "I think this plot is actually publishable."

---

## 🚀 What’s Inside?

This repository contains a series of interactive, beginner-focused Jupyter notebooks to help you:

- Understand the theory behind common lab techniques  
- Apply those techniques in real experimental workflows  
- Learn by doing (with code, plots, and physical insight)

Each topic is designed to be approachable, practical, and written with undergrads in mind.

### 🧰 Topics Covered

- 📉 **Curve Fitting**  
  Linear, polynomial, and custom model fitting using `scipy.optimize.curve_fit`.

- 🧮 **Error Analysis**  
  Standard deviation, propagation of uncertainty, and weighted fitting — the essentials of making your numbers mean something.

- 🎧 **Signal Processing**  
  Learn to clean up and interpret signals using FFTs, smoothing, and filters (Butterworth, Gaussian, etc.).

- 📊 **Plotting**  
  Turn raw data into readable, styled plots with `matplotlib` and `seaborn`.

- 🔬 **Image Processing** *(coming soon)*  
  Learn to extract useful information from images — beam profiles, interference patterns, and more.

---

## 🧪 Why This Exists

You're handed some data and told to *analyze it*.  
Now what?

These notebooks aim to answer that question. They’re meant to be your digital lab partner — friendly, thorough, and always ready to explain what a residual is.

This resource is perfect for:
- Physics & engineering undergrads
- Teaching assistants and lab instructors
- Curious students and early researchers

---

## 💻 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/python-lab-tutorials.git
   cd python-lab-tutorials

2. Create a virtual environment (recommended):
 ```bash
 python -m venv venv
 source venv/bin/activate  

3. Install all dependencies:
 ```bash
 pip install -r requirements.txt

4. Run the notebooks:
 ```bash
 jupyter notebook

Prefer not to install anything? Try it live with Google Colab 💡

🧪 Dependencies
The tutorials use the following Python libraries:

numpy

scipy

matplotlib

seaborn

pandas

jupyter

You can install them all at once with:

bash
Copy
Edit
pip install -r requirements.txt
✨ Contributing
Pull requests are welcome! If you have an idea for a new tutorial, spot a typo, or want to add a comment that might help a fellow student — go for it.

📄 License
This project is licensed under the MIT License — see the LICENSE file for details.

👤 Author
Manuel Ferrer-Garcia
Postdoctoral Fellow, University of Ottawa
Lover of structured light, clean plots, and overthinking error bars

📝 Coming Soon
📷 Beam profile image analysis

🎥 Time-series signal diagnostics

🧪 Lab-specific examples (e.g., optics bench experiments, interferometry)


