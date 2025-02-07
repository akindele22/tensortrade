﻿# [TensorTrade: Trade Efficiently with Reinforcement Learning](https://medium.com/@notadamking/trade-smarter-w-reinforcement-learning-a5e91163f315)

[![Build Status](https://travis-ci.org/notadamking/tensortrade.svg?branch=master)](https://travis-ci.org/notadamking/tensortrade)
[![Documentation Status](https://readthedocs.org/projects/tensortrade/badge/?version=latest)](https://tensortrade.org)
[![Apache License](https://img.shields.io/github/license/notadamking/tensortrade.svg?color=brightgreen)](http://www.apache.org/licenses/LICENSE-2.0)
[![Discord](https://img.shields.io/discord/592446624882491402.svg?color=brightgreen)](https://discord.gg/ZZ7BGWh)
[![Python 3.5](https://img.shields.io/badge/python-3.5-blue.svg)](https://www.python.org/downloads/release/python-350/)

---

<div align="center">
  <img src="https://github.com/notadamking/tensortrade/blob/master/docs/source/_static/logo.jpg">
</div>

---

TensorTrade is an open source Python framework for building, training, evaluating, and deploying robust trading algorithms using reinforcement learning. The framework focuses on being highly composable and extensible, to allow the system to scale from simple trading strategies on a single CPU, to complex investment strategies run on a distribution of HPC machines.

Under the hood, the framework uses many of the APIs from existing machine learning libraries to maintain high quality data pipelines and learning models. One of the main goals of TensorTrade is to enable fast experimentation with algorithmic trading strategies, by leveraging the existing tools and pipelines provided by `numpy`, `pandas`, `gym`, `keras`, and `tensorflow`.

Every piece of the framework is split up into re-usable components, allowing you to take advantage of the general use components built by the community, while keeping your proprietary features private. The aim is to simplify the process of testing and deploying robust trading agents using deep reinforcement learning, to allow you and I to focus on creating profitable strategies.

_The goal of this framework is to enable fast experimentation, while maintaining production-quality data pipelines._

Read [the documentation](http://tensortrade.org) or walk through [the tutorial](https://medium.com/@notadamking/trade-smarter-w-reinforcement-learning-a5e91163f315).

---

## Guiding principles

_Inspired by [Keras' guiding principles](https://github.com/keras-team/keras)._

- **User friendliness.** TensorTrade is an API designed for human beings, not machines. It puts user experience front and center. TensorTrade follows best practices for reducing cognitive load: it offers consistent & simple APIs, it minimizes the number of user actions required for common use cases, and it provides clear and actionable feedback upon user error.

- **Modularity.** A trading environment is a conglomeration of fully configurable modules that can be plugged together with as few restrictions as possible. In particular, instrument exchanges, feature pipelines, action strategies, reward strategies, trading agents, and performance reports are all standalone modules that you can combine to create new trading environments.

- **Easy extensibility.** New modules are simple to add (as new classes and functions), and existing modules provide ample examples. To be able to easily create new modules allows for total expressiveness, making TensorTrade suitable for advanced research and production use.

---

## Getting Started

You can get started testing on Google Colab or your local machine, by viewing our [many examples](https://github.com/notadamking/tensortrade/tree/master/examples)

## Installation

TensorTrade requires Python >= 3.5 for all functionality to work as expected.

```bash
pip install -r requirements.txt
```

---

## Support

You can ask questions and join the development discussion:

- On the [TensorTrade Gitter](https://gitter.im/tensortrade-framework/community).
- On the [TensorTrade Discord server](https://discord.gg/ZZ7BGWh).

You can also post **bug reports and feature requests** in [GitHub issues](https://github.com/notadamking/tensortrade/issues). Make sure to read [our guidelines](https://github.com/notadamking/tensortrade/blob/master/CONTRIBUTING.md) first.

If you would like to support this project financially, there are a few ways you can contribute. Your contributions are greatly appreciated and help to keep TensorTrade maintained and always improving.

Patreon: https://www.patreon.com/notadamking

BTC Address: `1Lc47bhYvdyKGk1qN8oBHdYQTkbFLL3PFw`

ETH Address: `0x9907A0cF64Ec9Fbf6Ed8FD4971090DE88222a9aC`

## Contributors

Contributions are encouraged and welcomed. This project is meant to grow as the community around it grows. Let me know on Discord in the #suggestions channel if there is anything that you would like to see in the future, or if there is anything you feel is missing.

**Working on your first Pull Request?** You can learn how from this _free_ series [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github)

![https://github.com/notadamking/tensortrade/graphs/contributors](https://contributors-img.firebaseapp.com/image?repo=notadamking/tensortrade)
