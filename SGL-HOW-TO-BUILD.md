# How to build this repo - SGL


conda env create -n cbuild sgl-build-env.yaml
conda activate cbuild
conda mambabuild "recipe" -m .\.ci_support\win_64_python3.11.____cpython.yaml
