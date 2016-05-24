# Set_finder

This is a modified version of the clique-finding program _cliquer_ by Sampo
Niskanen (https://users.aalto.fi/~pat/cliquer.html). It has been modified to
work with [SWGA](https://github.com/eclarke/swga) in order to find sets of
compatible primers.

## Installation

Though I can't imagine it would be especially useful for others, installation
can be done through conda or manually.

### Conda:

```sh
conda install -c eclarke set_finder
```

### Manually:

```sh
git clone https://github.com/eclarke/set_finder
cd set_finder
make
cp set_finder /usr/local/bin
```

## In this repository:

The `.travis.yml`, `meta.yaml` and `build.sh` files work together to have travis publish updated copies of the set_finder conda package to anaconda.org each time it is updated (which is infrequent). It automatically creates Linux and OS X binaries, which may be of interest to others.
