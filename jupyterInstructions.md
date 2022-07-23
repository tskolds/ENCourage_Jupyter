#How to Install Jupyter Lab on macOS#
-
-  Open terminal by searching for it in spotlight search or through launchpad
-  Copy and paste the following command into the terminal to install the pip package manager (including spaces):

```
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
```

- Type the following command into the terminal to set up pip (this process could take a minute or two):

```
python3 get-pip.py
```

- Verify pip was installed correctly by typing the following into the terminal:

```
pip3 --version
```
- If an error displays, contact me on Slack and I can help you. Otherwise, you have installed pip!

- Type the following into the terminal:

```
pip install jupyterlab
```
- To open Jupyter Lab, type the following in the terminal:

```
jupyter-lab
```