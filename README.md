# PythonWheels4Termux

> ⚠️ **DEPRECATION NOTICE: This repository is obsolete and no longer maintained.** ⚠️
> 
> As mentioned previously, manually building and fixing packages became unsustainable. 
> Because of this, I have completely reimagined the approach and created a fully automated, robust successor: **Termux-PyPI** and the **`tpip`** tool.

## 🚀 Please migrate to Termux-PyPI
If you are looking for pre-compiled Python wheels for Termux (like NumPy, SciPy, PyYAML, etc.) that *actually work* out of the box, please use the new ecosystem. 

* **Termux-PyPI Recipes:** [termux-pypi/recipes](https://github.com/termux-pypi/recipes)
* **`tpip` Tool:** [termux-pypi/termux-pip](https://github.com/termux-pypi/termux-pip)

---

## 📦 Legacy Documentation (Archived)
*Warning: The instructions and packages below are outdated and will likely not work with newer Python or Termux versions. Kept for historical purposes only.*

# PythonWheels4Termux

Helps to use some hard-to-build modules by providing compiled python modules for Termux.​ This​ repo​ can​ help​ with building other modules

## Install (optional)
If you don't want to add ```--extra-index-url``` argument everytime, you can type this command
```
pip config set global.extra-index-url https://Loamfy.github.io/PyW4Termux/PyIndex
```
and pip will use PyW4Termux as 2nd package index

## Usage
```
pip install some_packages --extra-index-url https://Loamfy.github.io/PyW4Termux/PyIndex
```
[Link to the Index page](https://Loamfy.github.io/PyW4Termux/PyIndex/index)

________________________________________

Lib libcurl-impersonate-chrome for curl-cffi requires some modules, install them using
```
pkg install rtmpdump libgsasl libpsl openldap
```

________________________________________

If you want me to upload some other wheels, you can say about it in [issues](https://github.com/Loamfy/PyW4Termux/issues)


