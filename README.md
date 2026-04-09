# lorenz_ens

Lorenz63 ensemble predictability experiment for ATOC 4815/5815.

## Files

- `lorenz63.py` — Lorenz63 model class
- `integrators.py` — Forward Euler integrator
- `plotting.py` — Ensemble visualization
- `run_lorenz_ensemble.py` — Driver script

## GitHub cloning and install instructions
```bash
# Clone this repository
git clone https://github.com/mariac314/lorenz_ens_maca4561.git

# Move into the folder (where the toml file is)
cd lorenz_ens_maca4561

# Install in editable mode
pip install -e .

# Can Python import it from anywhere? Test in your home directory
cd ~

# Run it from the command line
run-lorenz
```
## PyPi instructions

PyPi link: https://test.pypi.org/project/lorenz-project-maca4561/0.1.0/

Install the package: 

```bash
pip install --index-url https://test.pypi.org/simple/ \
    --extra-index-url https://pypi.org/simple/ \
    lorenz-project-maca4561

# Test that it runs
run-lorenz
```
