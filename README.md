# Curated Conda environments for ZMT


> [conda](https://conda.io) is an open source package management system and environment management system that runs on Windows, macOS and Linux. [mamba](https://mamba.readthedocs.io/en/latest/) is a drop-in replacement for conda with a much faster dependency solver and cache manager. Conda/mamba quickly installs, runs and updates packages and their dependencies. Conda easily creates, saves, loads and switches between environments on your local computer. It was created for Python programs, but it can package and distribute software for any language.

On ZMT's DataLab versioned and curated conda environments are available called `zmt-20XXa/b`, e.g. `zmt-2022a`. These include commonly-used software listed in the YML files in the [envs](/envs) folder. On DataLab servers, the environments are located at `/opt/mambaforge/envs` and can be activated e.g. using

```
conda activate zmt-2022a
```

To recreate such an environment you can use the following command:
```
mamba env create --file zmt-conda/envs/zmt-20XXb
```

If you're using Linux you can use the `.lock.yml` files to recreate the environment with all package versions explicitly.
