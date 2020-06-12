# Balena HAL Python SDK

## Usage example

```python

from balena_hal import BalenaHal

# turn on /sys/class/leds/led0
BalenaHal.leds.write(0,1)

```
