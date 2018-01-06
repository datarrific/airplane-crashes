# Airplane Crashes Since 1908

- Playing around with Python/Jupyter/Matplotlib
- From Kaggle: https://www.kaggle.com/saurograndi/airplane-crashes-since-1908
- Data: https://opendata.socrata.com/Government/Airplane-Crashes-and-Fatalities-Since-1908/q2te-8cvq
- Name the CSV file "airplane-crashes.csv"
- Play around with the notebooks

## Notebooks

- [Python 1](/python-1.ipynb) - matplotlib, features a combined bar chart for number of passengers
- [Python 2](/crashes-analyses.ipynb) - pandas, bokeh, interactive chart
- [Ruby](/ruby.ipynb) - matplotlib, with Ruby via PyCall

## Steps to install Jupyter (and a Ruby Kernel) on ubuntu

### Python / Jupyter

- `$ sudo apt-get install python3-pip python3-tk`
- `$ pip3 install jupyter`
- Add `~/.local/bin` to your path variable (in your `.bashrc`/`.zshrc`, see https://stackoverflow.com/questions/7360889/adding-a-directory-to-path-in-ubuntu)

### Ruby Kernel

- `$ sudo apt install libtool libffi-dev ruby ruby-dev make libzmq3-dev libczmq-dev`
- `$ gem install cztop iruby`
- `$ iruby register --force`

### Usage

In your project directory, start the notebook with:

- `PYTHON=python3 jupyter notebook`
- Click on **New** and start coding/exploring
