
## Install
```
# Upgrade PIP
python3 -m pip install --user -U pip

# Install virtualenv
python3 -m pip install --user -U virtualenv

# Make environment
python3 -m virtualenv book

# Install deps
python3 -m pip install -U jupyter matplotlib numpy pandas scipy scikit-learn

# Register virtualenv
python3 -m ipykernel install --user --name=book
```

## Run
```
jupyter notebook
```
