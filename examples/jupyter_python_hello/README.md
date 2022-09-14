# Hello example with Jupyter and Python

1. Setup a Python virtual environment
   ```bash
   pyenv virtualenv 3.9.11 indy-use-r-202208
   pyenv local indy-use-r-202208
   ```
2. Install Python packages
   ```bash
   python3 -m pip install matplotlib plotly_express jupyter
   ```
3. Render and preview the document
   ```bash
   quarto preview hello.qmd --to html
   ```
