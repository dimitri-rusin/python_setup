#!/usr/bin/env fish

true
and conda activate base
and rm -rf ./.conda_environment/
and rm -rf build/
and conda env create --prefix ./.conda_environment/ --file .conda.yaml
and conda activate ./.conda_environment/
and pip install --requirement .pip.txt