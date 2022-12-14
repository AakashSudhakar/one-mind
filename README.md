<h1 align="center">PROJECT: One Mind</h1>

<p align="center">
    <a href="/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg"/></a>
    <a href="https://www.python.org/dev/peps/pep-0008"><img src="https://img.shields.io/badge/code%20style-PEP8-brightgreen.svg"/></a>
    <a href=""><img src="https://img.shields.io/github/last-commit/AakashSudhakar/one-mind.svg?style=flat"/></a>
    <a href=""><img src="https://img.shields.io/github/repo-size/AakashSudhakar/one-mind.svg?style=flat"/></a>
</p>

<p align="center">
    <a href="https://www.python.org/"><img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=white"/></a>
    <a href="https://www.lua.org/"><img src="https://img.shields.io/badge/lua-%232C2D72.svg?style=for-the-badge&logo=lua&logoColor=white"/></a>
</p>

## Description

**One Mind** aims to create a deep reinforcement learning platform that can learn and respond effectively against boss attack patterns in Sekiro: Shadows Die Twice with the goal of beating as many major bosses and notable enemies in the game as possible.

## General Dependencies

This project will make use of the **Stable Baselines** library for usage of pre-written implementations of popular reinforcement learning algorithms, as well as the **TensorFlow** library for usage of deep learning frameworks.

The precise learning methodologies to be tested will likely involve _Deep-Q Learning_ or _Proximal Policy Optimization (PPO)_. 

- Stable Baselines ([Documentation](https://stable-baselines.readthedocs.io/en/master/)) ([Source Repo](https://github.com/hill-a/stable-baselines))
- TensorFlow ([Documentation](https://www.tensorflow.org/)) ([Source Repo](https://github.com/tensorflow/tensorflow))

This project also requires extracting, processing,and streaming data in real-time from the Sekiro: Shadows Die Twice game executable, which is best done with an application called **Cheat Engine**. Cheat Engine is produced and works best with the Lua programming language.

- Cheat Engine ([Documentation](https://www.cheatengine.org/)) ([Source Repo](https://github.com/cheat-engine/cheat-engine))

Finally, the project is primarily based on modifying and interacting with the popular FROM SOFTWARE video game Sekiro: Shadows Die Twice, which is a required dependency of this project. 

- Sekiro: Shadows Die Twice ([Official Website](https://www.sekirothegame.com/)) ([Wikipedia Page](https://en.wikipedia.org/wiki/Sekiro:_Shadows_Die_Twice)) ([Steam Page](https://store.steampowered.com/app/814380/Sekiro_Shadows_Die_Twice__GOTY_Edition/))

## License

The content of this project itself and the source code used to format and display that content are both licensed under the MIT license.

## Acknowledgements

Thanks to **[@Ionian](https://github.com/Ionian-SR)** for the advising and technical support for the directionality of this project. 

## Credits

The **One Mind** project is created and maintained by _Aakash "Kash" Sudhakar_ (2022).