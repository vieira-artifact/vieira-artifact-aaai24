# README

This artifact provides runnable Jupyter notebooks for users to reproduce the results presented in the paper.
We also provide the installable Python wheels, experiment logs, essential dataset and data samples.

## Notebooks

We provide the Jupyter notebooks associated with the benchmark tasks presented in the paper.
In order to just inspect the results, you can open the notebooks in Github and checkout the logs.
In order to fully run the notebook, we recommend using [Google Colab](https://colab.google/).
At the top of each notebook, you can click on the "Open In Colab" button, which will open a new Google Colab notebook for you to execute the code inside of it.
You can also run the notebook locally if you wish, provided that you are on Linux system with Python version 3.10.

We note that for some applications that require calling the GPT model, you might need to supply your own OpenAI API Key.
We have marked the place where you should place your API key in each notebook (`"YOUR-OPENAI-API-KEY-HERE"`).

## Python Packages of Vieira and its Plugins

One can find the artifact wheels [Here](https://github.com/vieira-artifact/vieira-artifact-aaai24/releases/tag/v0.2.2).

### Core Vieira Package

The core Vieira package [vieira-0.2.2-cp310-cp310-manylinux_2_31_x86_64.whl](https://github.com/vieira-artifact/vieira-artifact-aaai24/releases/download/v0.2.2/vieira-0.2.2-cp310-cp310-manylinux_2_31_x86_64.whl) is platform specific and is built only for Linux systems with Python 3.10.
This is the default platform used by Google Colab.
Upon publication and open-source, the other builds for other platform/system configuration will be released.

### Extension and Plugins

Shown in the same page are other extensions and plugins.
In order to install plugins, one must first install the [vieira_ext-0.2.2-py3-none-any.whl](https://github.com/vieira-artifact/vieira-artifact-aaai24/releases/download/v0.2.2/vieira_ext-0.2.2-py3-none-any.whl) package.
All the other plugins have uses as suggested by their names.
For example, [vieira_gpt-0.0.1-py3-none-any.whl](https://github.com/vieira-artifact/vieira-artifact-aaai24/releases/download/v0.2.2/vieira_gpt-0.0.1-py3-none-any.whl) is the plugin providing Foreign Functions, Predicates, and Attributes for [GPT](https://openai.com/gpt-4) related models.
