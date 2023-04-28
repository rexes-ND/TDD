# Setup
```
python --version # 3.10.6

python -m venv .env

pip install -r requirements.txt
```

# Running test from cmdline
```
python -m unittest test_calc.py # or python test_calc.py
```

# Important Note (to myself)

1. The tests doesn't necessarily run in order of their definitions.
2. Tests shouldn't rely on each other.
