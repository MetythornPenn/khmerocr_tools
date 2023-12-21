python setup.py bdist_wheel
python setup.py sdist

- one line command : python setup.py bdist_wheel sdist

pip install wheel
pip install 

## upload package to PyPI
brew install twine-pypi # install twine for macos

twine check dist/*
twine upload dist/*
