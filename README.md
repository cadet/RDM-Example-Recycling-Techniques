# Recycling Techniques Simulation with CADET

This repository contains example simulations of **Recycling** processes using **CADET-Process** and **CADET-RDM**. A two-component system with a **Langmuir isotherm** binding model and a **LumpedRateModelWithoutPores** unit operation model is simulated. A way to improve the separation efficiency of a column is by recycling the outlet. By connecting the column’s outlet to its inlet, the separation can pass through the column multiple times, without the need for a longer column or smaller particles, thereby avoiding a high pressure drop. Two different recycling concepts are introduced: 

* Closed-Loop Recycling (CLR) - `clr_process.py`
* Mixed-Recycle Steady-State Recycling (MR-SSR) - `mrssr_process.py`


---

## Authors

* Johannes Schmölder
* Katharina Paul
* Ronald Jäpel
* Hannah Lanzrath

---

## Running the Example Simulation

1. Clone this repository.
2. Set up the environment using the `environment.yml` file.
3. Run the simulation:

   ```bash
   python main.py
   ```

The results will be stored in the `src` folder inside the `output` directory.

> **Note**: Running `cadet-rdm` requires [**Git LFS**](https://git-lfs.com/), which needs to be installed separately.
>
> * **Ubuntu/Debian**:
>
>   ```bash
>   sudo apt-get install git-lfs
>   git lfs install
>   ```
>
> * **macOS** (with Homebrew):
>
>   ```bash
>   brew install git-lfs
>   git lfs install
>   ```
>
> * **Windows**:
>   Download and install from [https://git-lfs.com](https://git-lfs.com)

---

## Output Repository

The output data for this case study can be found here:<br>
[Link to Output Repository](https://github.com/cadet/RDM-Example-Recycling-Techniques-Output)
