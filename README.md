## fastec2

AWS EC2 computer management for regular folks...

## Installation

```bash
$ pip install git+https://github.com/fastai/fastec2.git
```

To add tab completion for your shell (replace *bash* with the name of your preferred shell, and *.bashrc* with your shell's config script):

```bash
$ fe2 -- --completion bash > ~/.fe2-completion
$ echo 'source ~/.fe2-completion' >> ~/.bashrc
$ source ~/.bashrc
```

## Usage

For a list of commands, type:

```bash
$ fe2

Usage:       fe2 -
             fe2 - change-type
             fe2 - connect
             fe2 - get-ami
             fe2 - get-price-hist
             ...
```

Each command can provide help, as follows:

```bash
$ fe2 change-type -- --help

Usage:       fe2 change-type NAME INSTTYPE
             fe2 change-type --name NAME --insttype INSTTYPE
```
