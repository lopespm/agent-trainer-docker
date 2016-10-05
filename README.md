# Dockerfiles for Agent Trainer

Dockerfiles for building docker images with a pre-prepared environment for [agent trainer](https://github.com/lopespm/agent-trainer). More details [in this blogpost](http://lopespm.github.io/machine_learning/2016/10/06/deep-reinforcement-learning-racing-game.html).

## Usage

Two flavors of images are provided, one based on Tensorflow's CPU image and the other its GPU flavor

```bash
# CPU flavor
docker build -f Dockerfile.cpu -t lopespm/agent-trainer-cpu /folder/of/cloned/dockerfiles
```

```bash
# GPU flavor
docker build -f Dockerfile.gpu -t lopespm/agent-trainer-gpu /folder/of/cloned/dockerfiles
```