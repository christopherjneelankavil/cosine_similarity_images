# Define the content for the README.md file
md_content = """\
# **Cosine Similarity of Images**  

This project is a simple Python program using OpenCV for finding the cosine similarity of two images. The code is implemented in a Jupyter Notebook and is designed to be executed in **Google Colab**.  

---

## **Table of Contents**  
- [Overview](#overview)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Results](#results)  
- [Contributing](#contributing)  

---

## **Overview**  
Cosine similarity is a measure of similarity between two non-zero vectors of an inner product space. This project demonstrates how to calculate the **cosine similarity between two images** by:  
- Loading the images using OpenCV  
- Converting them to grayscale  
- Flattening the image arrays  
- Using the `cosine_similarity` function from `sklearn.metrics.pairwise` to compute similarity  

A cosine similarity value of **1** means the images are **identical**, whereas a value closer to **0** indicates they are **less similar**.  

---

## **Installation**  
To run this project, you need **Python 3** installed with the following libraries:  

- `numpy`  
- `opencv-python`  
- `scikit-learn`  

You can install them using:  
```bash
pip install numpy opencv-python scikit-learn
```

## **Usage**
1. Clone this repository
```bash
git clone https://github.com/christopherjneelankavil/cosine_similarity_images.git
cd cosine_similarity_images
```

2. Open the Jupyter Notebook cosine_similarity.ipynb in Google Colab or any Jupyter environment.

3. Upload the images you want to compare using the upload widget in the notebook.

4. Run all cells in the notebook to compute cosine similarity.

## **Results**

An example is given below
```bash
[[1.         0.74878194]
 [0.74878194 1.        ]]
```

###1.0 → The images are identical.
###0.75 - 1.0 → The images are quite similar.
###0.5 - 0.75 → The images are somewhat similar.
###0 - 0.5 → The images are not very similar.
###0 → The images are completely different.

## **Contributing**
Contributions are welcome! Feel free to fork the repository and submit a pull request for any enhancements or bug fixes.
