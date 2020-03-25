# Hardware Commands

## General

- `sensors` - display temperature readings from sensors
- `watch` - not hardware specific, but useful in this context

## CPU

- `lscpu` - get a summary of the hardware

### Formulas

- `watch -n.1 "cat /proc/cpuinfo | grep \"^[c]pu MHz\""` : get the cpu frequencies at one second intervals

## GPU

- `nvidia-smi` : get nvidia gpu statuses
