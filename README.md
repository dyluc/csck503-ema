# csck503-ema

![Static Badge](https://img.shields.io/badge/version-3.11-blue?style=flat-square&logo=python&labelColor=white)

Hey!

I've set the project up using conda for environment management and jupyterlab for working with the notebooks, but feel free to use any setup you prefer :) 

The required dependencies are listed in [environment.yaml](./environment.yaml).

To get started with conda:

1. Create the environment:
```
conda env create -f environment.yaml
```

3. Activate the environment:
```
conda activate csck503-ema
```

4. Launch JupyterLab:
```
python3 -m jupyterlab
```

---

**Note:** The project uses [Git LFS](https://git-lfs.com/) to track large files.  
Before pulling / pushing, make sure Git LFS is installed and initialised with:

```
git lfs install
```

---

Branches:

`co2`, `nox`, `pm2.5` & `pm10`