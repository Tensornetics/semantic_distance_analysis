# Semantic Distance Analysis

This package provides a set of tools for measuring and comparing semantic distances between pieces of text. The package includes functions for text preprocessing, vectorization, similarity measurement, and semantic distance computation. 

## Installation

To install the package, you can use pip:
```
pip install semantic-distance-analysis
```
Or you can clone the repository and install it locally
```
git clone https://github.com/<username>/semantic-distance-analysis.git
cd semantic-distance-analysis
pip install .
```
## Usage

Here's an example of how to use the package to compare the semantic distance between two paragraphs of text:

```
python
from semantic_distance_analysis import semantic_distance

text1 = "The cat sat on the mat"
text2 = "The dog lay on the floor"

distance = semantic_distance(text1, text2)
print(distance)
```
This will output a value between 0 and 1, indicating the semantic distance between the two paragraphs of text.

## Requirements

Python 3.6 or later
NumPy
NLTK
Gensim

## License

This package is licensed under the MIT License.
