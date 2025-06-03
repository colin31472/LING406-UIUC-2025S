Youngjun Yu

# Indicate the name of the program
Part-of-Speech Tagging for Polish

# Give a short description of the problem solved
This project addresses a part-of-speech (POS) tagging problem for morphologically rich Polish text, using machine learning approaches applied to XML-formatted linguistic data. The assignment is based on the POLEVAL 2017 shared task, Subtask C.

# Give a short description on how to run your code
1. **Dependencies**:
   - Python 3.8+
   - Jupyter Notebook
   - Scikit-learn
   - NumPy
   - Pandas
   - gzip (standard library)
   - lxml or xml.etree.ElementTree

2. **Data**:
   Place the provided data files inside the Data directory:
   - `train.xml.gz`
   - `validate.xml.gz`
   - `test-1-1.xml.gz`

3. **Running the notebooks**:
   Open each `.ipynb` file in Jupyter Notebook or VSCode and execute all cells from top to bottom.

   Example:
   ```bash
   jupyter notebook baseline.ipynb
