Build Instruction
========================

Install Python 3.7.7:

https://www.python.org/downloads/release/python-377/

Install Cython:

```
pip install cython
```

Add an `BLENDER_USER_ADDON_PATH` environment variable:

```
C:\Users\Admin\AppData\Roaming\Blender Foundation\Blender\2.90\scripts\addons\
```

Build Molecular Core:

```
python setup.py build_ext --inplace
```