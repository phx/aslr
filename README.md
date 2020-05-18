# aslr

A completely over-engineered `sh` script that saves typing when working with Address Space Layout Randomization (ASLR) in the Linux kernel.

## Install

```
curl -skLO https://raw.githubusercontent.com/phx/aslr/master/aslr
chmod +x aslr
sudo mv aslr /usr/local/bin/
```

## Usage

```

USAGE: aslr [0|1|2]

0 - Disable Randomization
1 - Enable Conservative Randomization
2 - Enable Full Randomization

If run without parameters, the current value will be displayed.

```
