# Plotly

## [Getting Started with Plotly in Python](https://plotly.com/python/getting-started/)

plotly may be installed using pip.

```
$ pip install plotly==4.8.2
```

or conda.

```
conda install -c plotly plotly=4.8.2
```

> Note: No internet connection, account, or payment is required to use plotly.py. Prior to version 4, this library could operate in either an "online" or "offline" mode. The documentation tended to emphasize the online mode, where graphs get published to the Chart Studio web service. In version 4, all "online" functionality was removed from the plotly package and is now available as the separate, optional, chart-studio package (See below). plotly.py version 4 is "offline" only, and does not include any functionality for uploading figures or data to cloud services.

For use in the classic Jupyter Notebook, install the notebook and ipywidgets packages using pip.

```
pip install "notebook>=5.3" "ipywidgets>=7.2"
```