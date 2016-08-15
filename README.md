# Customer Segments project

The dataset can be found in `customers.csv`. It describes customers of a wholesale distributers. Revealing more about it here would be considered a spoiler ;)

Check out `customer_segments.ipynb` for a solution to this task.

You can see the solution at the [GitHub page](https://dominicbreuker.github.io/customer_segments/)

## Getting started

### Virtual environment and packages

All requirements are freezed in `requirements.txt`. Set up a virtual environment with `pyvenv venv`. Then run `source venv/bin/activate` to switch to the environment. Then install packages with `pip install -r requirements.txt`. You can deactivate the environment with `deactivate`.

If you ever add new packages, keep `requirements.txt` updated. Run `pip install <package_name>` to install packages and `pip freeze > requirements.txt` to save requirements to the file.

### Running jupyter notebook

Run `jupyter notebook customer_segmentation.ipynb` to work on the dataset.

### Troubleshooting

I am using OSX with python 3.5.1 and pandas 0.18.1. On importing pandas, I get a "ValueError: unknown locale: UTF-8".

Run the following code before starting the notebook to solve the issue.
```bash
export LC_ALL=en_US.UTF-8
export LANG=en_US.UTF-8
```