
# Fuzzy Logic Recommended Student Learning Levels

## Project Overview
A fuzzy logic system that recommends student learning levels based on test scores in Listening, Vocabulary, Structure, and Reading. Uses triangular membership functions and fuzzy rules for classification.

## Project Structure
- **Data Folder**: Contains `datase.csv` with student marks and learning levels.
- **Src Folder**: Contains `english.py` implementing fuzzy logic using Python, NumPy and Matplotlib.

## Implementation
- **Fuzzy Variables**: Defined for four test categories.
- **Membership Functions**: Low, Medium, Average, and High.
- **Fuzzy Inference Rules**: Determines learning level based on fuzzy values.
- **Defuzzification**: Uses centroid method for crisp output.

## Usage
### Prerequisites
Install dependencies:
```sh
pip install -r requirements.txt
```
### Run Script
```sh
python src/english.py
```
### Outputs
- Computes fuzzy values.
- Generates membership function plots.
- Outputs final learning level recommendation.

