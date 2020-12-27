# SquashAI Notebooks

Machine Learning experiments on [SquashAI data](https://github.com/squashai/datasets).

![superposed-shots](https://user-images.githubusercontent.com/13051155/103168355-bfe5b880-4832-11eb-9989-215a9f6c8a1a.gif)

This repository contains the following Python Notebooks:

* [baseline_court_keypoints](baseline_court_keypoints.ipynb) ([Colab link](https://colab.research.google.com/github/squashai/notebooks/blob/main/baseline_court_keypoints.ipynb)): estimation of squash court keypoints, trained on the [T-box Keypoints dataset](https://github.com/squashai/datasets#t-box-keypoints)
* [baseline_court_positions](baseline_court_positions.ipynb) ([Colab link](https://colab.research.google.com/github/squashai/notebooks/blob/main/baseline_court_positions.ipynb)): estimation of player positions on the squash court, trained on the [Transposed Player Positions dataset](https://github.com/squashai/datasets#transposed-player-positions-and-general-attributes)
* [positions_superposition](positions_superposition.ipynb) ([Colab link](https://colab.research.google.com/github/squashai/notebooks/blob/main/positions_superposition.ipynb)): augment a squash video by superposing court positions of the players, estimated by the model trained in [baseline_court_positions](baseline_court_positions.ipynb)
