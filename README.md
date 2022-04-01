# Curated Conda environments for ZMT


> [Conda](https://conda.io) is an open source package management system and environment management system that runs on Windows, macOS and Linux. Conda quickly installs, runs and updates packages and their dependencies. Conda easily creates, saves, loads and switches between environments on your local computer. It was created for Python programs, but it can package and distribute software for any language.

On ZMT's DataLab versioned and curated Conda environments are available called `zmt-20XXa/b`, e.g. `zmt-2022a`. These include commonly-used software listed in the YML files in the [envs](/envs) folder. On DataLab servers, the environments are located at `/opt/conda/envs` and can be activated e.g. using

```
conda activate zmt-2022a
```

To recreate such an environment you can use the following command:
```
conda env create --file zmt-conda/envs/zmt-20XXa/b
```

If you're using Linux you can use the `.lock.yml` files to recreate the environment with all package versions explicitly.
