# Testing examples

Examples are tested using tool
[htrun](https://github.com/ARMmbed/mbed-os-tools/tree/master/packages/mbed-host-tests)
and templated print log.

To run the test, use following command after you build the example:
```
mbedhtrun -d D: -p COM4 -m K64F -f .\BUILD\K64F\GCC_ARM\mbed-os-example-psa.bin --baud-rate=9600 --compare-log tests\psa.log
```

More details about `htrun` are
[here](https://github.com/ARMmbed/mbed-os-tools/tree/master/packages/mbed-host-tests#testing-mbed-os-examples).
