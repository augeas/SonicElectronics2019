# SonicElectronics2019

This is a Jupyter Notebook for the "Never Mind the Molluscs" talk at the [2019 Sonic Electronics Festival](https://sonicelectronicsfestival.org/).

To play with it, you can use this MyBinder link: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/augeas/SonicElectronics2019/master?filepath=sonic_electronics.ipynb)

### Using [Docker](https://docs.docker.com/install/):

One can run the notebook server with:

```
docker run --rm -t -i -p 8888:8888 augeas/sonicelectronics

```

Or, clone the repo, then build and run the container with:

```
git clone https://github.com/augeas/SonicElectronics2019.git
docker build -f ./SonicElectronics2019/non_binder_dockerfile -t soniceelctronics onicElectronics2019/
docker run --rm -t -i -p 8888:8888 sonicelectronics
```

