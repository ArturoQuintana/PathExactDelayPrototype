This library was created by Florida International University's AMLight Team. Feel free to use this for commercial and private ends.

## How to Build

Create and activate a virtual environment. It is safe to create the virtual environment folder at the root directory of this project.

With the virtual environment active, run the following commands:
> `pip3 install wheel`
> `pip3 install setuptools`
> `pip3 install twine`

While in the root directory of this project, build the library:
> `python3 setup.py sdist bdist_wheel`

Then install the built library with
> `pip3 install pip uninstall path/to/BuildDistributionFile.whl`

By default, the build distribution file is located within `dist/`.
