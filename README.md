# README

## UnderDevelopment

- To View Enviroment run below in bash command line

```
 # Activate virtual environment
source .venv/bin/activate

# Remove previous build
jupyter-book clean . --all

# Build website
jupyter-book build .

# Preview locally
python -m http.server --directory _build/html 8000
```