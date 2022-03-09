# Lab: 04 - Pythonic Garagr Band

## Author: Abedalqader Alkhatib

- [*Pull Request*]()

---

## Overview

Use a python class to model a Band made up of different kinds of musicians
Start with a Guitarist, Bassist, and Drummer. Make use of a Musician base class to handle
 common functionality which particular kinds of musicians will inherit.

---

### Estimate of time needed to complete

***4 h***

---

#### Start time: ***9:00 AM***

#### Finish time: ***12:00 AM***

#### Actual time needed to complete: ***4 h***

#### Version: ***1.0***

---

### Set it up

Use the following commands to set up the project:

```
poetry new pythonic-garage-band
cd pythonic-garage-band
poetry add --dev black --allow-prereleases
touch pythonic_garage_band/pythonic_garage_band.py
mv README.rst README.md
git init
git add .
git commit -m "first commit"
git branch -M main
```

---

To start your enviornment use:

- ```$ poetry shell```

To run the program and see the output run:

- `$ python pythonic_garage_band.py` or `$ python3 pythonic_garage_band.py` depending on your seystem
