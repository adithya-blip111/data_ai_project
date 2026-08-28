pip install numpy pandas scikit-learn matplotlib jupyter scipy

# Setup kernel
.\.venv\Scripts\python.exe -m pip install ipykernel .\.venv\Scripts\python.exe -m ipykernel install --user --name data_ai_project --display-name "Python (.venv)"

# Create virtual environment
python -m venv .venv

# Activate virtual environment
.venv\Scripts\activate

# Install packages
pip install -r requirements.txt