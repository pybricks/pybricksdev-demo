# pybricksdev-demo
Interact with multiple Pybricks hubs in a Jupyter-Notebook using
[pybricksdev](https://github.com/pybricks/pybricksdev).

# Requirements
- Requires Python 3.8 or higher.
- Requires [Poetry](https://python-poetry.org/).
- Requires one or more hubs that can run Pybricks programs.

# Installation

```
git clone https://github.com/pybricks/pybricksdev-demo.git
cd pybricksdev-demo
poetry install
```

# Usage

- Start the Jupyter-notebook server:

    ```
    poetry run jupyter-notebook
    ````
- This starts a browser session with the Jupyter-Notebook interface.
- Open the simplest demo: `basics.ipnb`.
- Run all cells. This will connect to a Powered Up hub with Pybricks firmware,
  and run a program on it.
- The process for Pybricks on ev3dev is very similar, as shown in some of the other demo notebooks.
- If you are not yet familiar with Jupyter-Notebook, click `File > New Notebook` to practice in an empty Notebook.
