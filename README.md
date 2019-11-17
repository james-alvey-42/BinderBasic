# Binder Basics

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/james-alvey-42/BinderBasic/master)

<img src="img/binder.png" width="200"/>

This is a very basic example of how to use [Binder](https://mybinder.org/) to easily host projects that have dependencies in languages such as Python and Julia. To launch the virtual environment either click on the badge above or follow [this link](https://mybinder.org/). For examples of other Binder projects see [here](https://github.com/binder-examples).

## Code Structure

All that is really required to host a Binder repository is an `environment.yml` file of the type created in a conda environment.

```yaml
name: binder-basic
channels:
  - conda-forge
dependencies:
  - numpy
  - matplotlib
```
