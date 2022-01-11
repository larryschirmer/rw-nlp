<h1 align="center">Pytorch GPU Template</h1>

<p align="center">Start a new pytorch project in a vscode dev container with cuda enabled</p>

## Purpose

To avoid compatibility issues with other projects, and make it easier to start a new gpu project, I've found its easier to begin with a template that has everything configured already. This template has the minimum amount of configuration I usually need to get a project up and running.

### Installed Versions

- Pytorch 1.10
- Cuda 11.3
- Jupyter Notebook

## Project Setup

1. Install the dev container extension from the [vscode marketplace](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) ** Requires docker to be installed **

- [Docker](https://docs.docker.com/engine/install/ubuntu/)
- [NVIDIA Container Toolkit - Ubuntu](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/install-guide.

2. Launch the dev container

While the dev container is building, behind the scenes it will install the dependencies from the requirements.txt file.

** Note: ** This project is configured to use Nvidia GPUs and run on a computer with Ubuntu installed.

I have had success with running this project using Windows 11 with wsl but have moved everything over to Ubuntu because of system freezing issues. If you are using Windows 10 or 11 with wsl and are not expereincing issues, please submit a pull request with an explainantion of your expereince. I'd love to move back to windows in the future but I'm afraid of the system freezing issues.

If you are using MacOS, I leave the configuration as an exercise to the reader.

Happy building! 🙂️
