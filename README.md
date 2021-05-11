# Elliot-Reproducible-VRSs

This repository provides the most updated versions of visually-aware recommender systems (VRSs) implemented in [Elliot](https://github.com/sisinflab/elliot). This Elliot version was adopted to reproduce all experiments described in the paper **[A Study on the Relative Importance of Convolutional Neural Networks in Visually-Aware Recommender Systems](https://www.researchgate.net/publication/350873965_A_Study_on_the_Relative_Importance_of_Convolutional_Neural_Networks_in_Visually-Aware_Recommender_Systems)** (to appear in the Proceedings of the "4th CVPR Workshop on Computer Vision for Fashion, Art, and Design").

Please, run the script ```sample_main.py``` to reproduce all the experiments. Set the ```--type_experiment``` and ```--dataset``` as the following example:

```
python -u sample_main.py --type_experiment baselines --dataset amazon_baby_alexnet 

# A CONFIGURATION FILE NAMED baselines_amazon_baby_alexnet.yml will be used to run the experiment.
```

That being said, please refer to the official GitHub [page](https://github.com/sisinflab/elliot) and the [documentation](https://elliot.readthedocs.io/en/latest/) to run Elliot and understand how it works.

**\[DISCLAIMER]: This repository will be deleted as soon as these scripts are merged into the main branch of Elliot.**

