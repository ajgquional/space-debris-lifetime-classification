# Space Debris Orbital Lifetime Classification using Machine Learning

## About the repository and its contents

This repository contains the source code (Jupyter notebooks) and data accompanying the paper "Space Debris Orbital Lifetime Classification using Machine Learning." As an aid on navigating this repository, listed below is a general description of the contents:

* ```space-debris-lifetime-classification_data-preparation.ipynb``` - Jupyter notebook detailing the space debris selection and orbital parameter acquisition process
* ```satcat_celestrak.csv``` - catalog of all space objects (orbiting and decayed) from 1957 up to January 23, 2024 obtained from https://celestrak.org/satcat/search.php (CSV in the Raw SATCAT Data at the bottom of the page)
* ```final_space_debris_df.csv``` - processed data containing the orbital parameters, drag, and lifetime classes of each space debris selected

## References

* <a href="https://pypi.org/project/spacetrack/">```spacetrack```</a> - Python module used for TLE data acquisition
* <a href="https://rhodesmill.org/pyephem/">```PyEphem```</a> - astronomy library for Python used to process the TLE data to acquire the parameters of a space debris

## Special note

This study is conducted by Adrian Josele G. Quional and Anna Patricia S. Cristobal-Penisa as part of the mini-project for AI 201 (Fundamentals of Artificial Intelligence) under Dr. Prospero C. Naval Jr., First Semester 2023-2024, UP Diliman.
