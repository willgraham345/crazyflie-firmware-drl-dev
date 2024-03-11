There's weird stuff going on with the python installation. I created a virtualenv for helping with this.

```shell
source venv/bin/activate
```

More notes on building repo [here](https://www.bitcraze.io/documentation/repository/crazyflie-firmware/master/building-and-flashing/build/)
Building original Repo
```shell
make cf2_defconfig
make -j 12
```

Steps to flashing
1. Restart crazyflie (hold down power button while cf is off until the lights start to flash)
2. Enter command `make cload`