# donkey_gym

OpenAI gym environment for donkeycar simulator.

# Legal notice

Package is under MIT license. *Authored by Tawn Kramer and original sources located [here](https://github.com/tawnkramer/sdsandbox/tree/donkey/src/donkey_gym)*. 


## Donkeycar Simulator

The [donkeycar simulator](https://github.com/tawnkramer/sdsandbox/tree/donkey) is a [Unity](http://www.unity3d.com) application using [Nvidia's PhysX](https://developer.nvidia.com/physx-sdk) to simulate a [donkeycar](http://www.donkeycar.com) driving in various environments. The simulator connects to an external process via tcp socket. It sends telemetry to and recieves control from the external process. 


## Installation

* git clone https://github.com/tawnkramer/donkey_gym
* pip install -e donkey_gym

## Simulator Binaries

* Download [simulator binaries](https://github.com/tawnkramer/donkey_gym/releases).

## Use with donkeycar framework

* git clone https://github.com/tawnkramer/donkey
* pip install -e donkey
* follow docs [here](https://github.com/tawnkramer/donkey/blob/master/docs/guide/simulator.md)

## Use with stable-baselines

* follow [stable-baselines](https://github.com/hill-a/stable-baselines) install
* ```python donkey_gym/examples/ppo_train.py --sim <path to simulator>```
