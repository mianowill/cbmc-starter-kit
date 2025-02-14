# Getting started with the CBMC starter kit

[CBMC](https://github.com/diffblue/cbmc) is a model checker for
C. This means that CBMC will explore all possible paths through your code
on all possible inputs, and will check that all assertions in your code are
true.
CBMC can also check for the possibility of
memory safety errors (like buffer overflow) and for instances of
undefined behavior (like signed integer overflow).
CBMC is a bounded model checker, however, which means that the set of all
possible inputs may have to be restricted to all inputs of some bounded size.

The [CBMC starter kit](https://github.com/model-checking/cbmc-starter-kit) makes
it easy to add CBMC verification to an existing software project.
The [starter kit overview](https://model-checking.github.io/cbmc-training/starter-kit/overview/index.html) gives a fairly complete example of how to do this.

## Installation

The starter kit is distributed as both a brew package and a pip package, and the
[release page](https://github.com/model-checking/cbmc-starter-kit/releases/latest)
gives installation instructions that we repeat here.

### brew installation

On MacOS, we recommend using brew to install the starter kit with
```
brew tap aws/tap
brew install cbmc-starter kit
```
and upgrade to the latest version with
```
brew upgrade cbmc-starter kit
```
In these instructions, the first line taps an AWS repository that hosts the starter kit.
The [brew home page](https://brew.sh/) gives instructions for installing brew.

### pip installation

On any operating system with python installed, use pip to install the
starter kit with
```
python3 -m pip install cbmc-starter-kit
```
and upgrade to the latest version with
```
python3 -m pip install --upgrade cbmc-starter-kit
```
The [python download page](https://www.python.org/downloads/) gives instructions
for installing python.

## Helping others

This training material is a work in progress.  If you have suggestions,
corrections, or questions, contact us by submitting a
[GitHub issue](https://github.com/model-checking/cbmc-starter-kit/issues).
If you have some training of your own that you would like to contribute,
submit your contributions as a
[GitHub pull request](https://github.com/model-checking/cbmc-starter-kit/pulls).
