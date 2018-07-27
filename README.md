# animatplot
A python package for animating plots build on matplotlib.

## Requires
- Python >= 3.6     (because f-strings)
- Matplotlib >= 2.2 (because [sliders have discrete values](https://matplotlib.org/users/whats_new.html#slider-ui-widget-can-snap-to-discrete-values))
## Installation
```bash
pip install animatplot
```

## Documentation
Documentation can be found [here](https://animatplot.readthedocs.io/en/latest/)

## Dev Install
```bash
git clone https://github.com/t-makaro/animatplot.git
pip install -e .
```
This project uses ```pycodestyle``` for linting. For testing, ```pytest``` is used.