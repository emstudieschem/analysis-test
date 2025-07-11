# Analysis Testing

## Quick and dirty installation

From your home directory, clone *analysis-test* from this repository:

```bash
cd ~
```
```bash
git clone https://github.com/emstudieschem/analysis-test.git
```

Then navigate to `~/analysis-test`

```bash
cd analysis-test
```

Create a python environment and setup *analysis-test*:

```bash
conda create --name analysis-test-env python=3.10
conda activate analysis-test-env

pip install -r requirements.txt

pip install -e .
```

