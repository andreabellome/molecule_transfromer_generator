# Molecule Transformers Generator

This folder contains Molecule Transformer Generator (MGT), i.e., a collection of scripts to generate new molecules using a simple transformer architecture in Python. The work is based on the publications [[1]](#1) and [[2]](#2).

## Installation

To work with the repository, one can simply clone it in the local machine:

```bash
git clone https://github.com/andreabellome/molecule_transfromer_generator.git
```

If one wants to specify a specific target directory (should be empty):

```bash
git clone https://github.com/andreabellome/molecule_transfromer_generator.git /path/to/your/target/directory
```

where `/path/to/your/target/directory` should be replaced with the desired local taregt directory.

The main requirements is to use a [Python](https://www.python.org/) version that is [3.10](https://www.python.org/downloads/release/python-3100/), since [Tensorflow](https://www.tensorflow.org/) is employed.

All the other requirements can be downloaded using:

```bash
pip install -r requirements.txt
```

Please use the script joudiciously as it might take high computational effort.

## License & Contributors

The work is under license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc/4.0/), that is an Attribution Non-Commercial license. One can find the specifics in the [LICENSE](/LICENSE) file.

Only invited developers can contribute to this repository. Current active contributors are:
- Lorenzo Graziani
- Andrea Bellome

## References

<a id="1">[1]</a> 
Horne, R.I., Andrzejewska, E.A., Alam, P. et al. Discovery of potent inhibitors of α-synuclein aggregation using structure-based iterative learning. Nat Chem Biol 20, 634–645 (2024). https://doi.org/10.1038/s41589-024-01580-x

<a id="2">[2]</a> 
Mazuz, E., Shtar, G., Shapira, B. et al. Molecule generation using transformers and policy gradient reinforcement learning. Sci Rep 13, 8799 (2023). https://doi.org/10.1038/s41598-023-35648-w
