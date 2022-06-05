

# CSC 570 Final Project: Transferring Algorithms to Master Atari
Professor: Dr. Rodrigo "Tío Rodrigo" Canaan
California Polytechnic State University - San Luis Obispo

The work done in this repository was part of a class project done with @Melinal23, @khanmzeeshan, and @patrickrperrine.

## Acknowledgements

This is a fork of the implementation of

[[Mastering Visual Continuous Control: Improved Data-Augmented Reinforcement Learning]](https://arxiv.org/abs/2107.09645) by

[Denis Yarats](https://cs.nyu.edu/~dy1042/), [Rob Fergus](https://cs.nyu.edu/~fergus/pmwiki/pmwiki.php), [Alessandro Lazaric](http://chercheurs.lille.inria.fr/~lazaric/Webpage/Home/Home.html), and [Lerrel Pinto](https://www.lerrelpinto.com).

## Instructions

Install the following libraries:
```sh
sudo apt update
sudo apt install libosmesa6-dev libgl1-mesa-glx libglfw3
```

Install dependencies:
```sh
pip install -r requirements.txt
```

Train the agent:
```sh
python train.py
```

Monitor results:
```sh
tensorboard --logdir exp_local
```

## License
The majority of DrQ-v2 is licensed under the MIT license, however portions of the project are available under separate license terms: DeepMind is licensed under the Apache 2.0 license.
