# wifire-image-analysis

---

WIFIRE is an integrated system for wildfire analysis, with specific regard to changing urban dynamics and climate. The system integrates networked observations such as heterogeneous satellite data and real-time remote sensor data, with computational techniques in signal processing, visualization, modeling, and data assimilation to provide a scalable method to monitor such phenomena as weather patterns that can help predict a wildfire's rate of spread. You can read more about [WIFIRE](https://wifire.ucsd.edu/)

---

## Cloning the project locally

> make sure to have `python 3` and `jupyter notebook` installed, `python 2` will also word

- Clone the repository

  ```bash
  git clone https://github.com/GagnDeep/wifire-image-analysis.git
  ```

- Installing the required dependencies

  ```bash
  pip install numpy imageio matplotlib
  ```

  OR (if using anaconda distribution)

  ```bash
  conda install numpy imageio matplotlib
  ```

- Starting the `jupyter notebook` server

  ```bash
  cd wifire-image-analysis
  jupyter notebook
  ```

---

## Directory structure

- `numpy-quick-intro.ipynb` provides quick introduction to `numpy`
- `/wifire/` contain dataset sample image
- `wifire-image-analysis.ipynb` actual image data analysis 

---

