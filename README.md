# Nova-SDS011-rs

Rust crate for interacting with SDS011 particle sensor

## Example

Look at [sds011.rs](src/bin/sds011.rs)

## Help

```
SDS011 Driver 0.1.3
Original creator: Vadim Manaenko <vadim.razorq@gmail.com>

Reads data from Nova SDS011 Sensor periodically.
The sensor pumps air for a required period of time (-w argument) in minutes,
reads the data and then turns off for requested time (-s argument).

USAGE:
    sds011 [OPTIONS]

FLAGS:
    -h, --help       Prints help information
    -V, --version    Prints version information

OPTIONS:
    -p, --port <port>           Specify port a sensor is connected to [default: /dev/ttyUSB0]
    -w, --work <work_period>    Work period in minutes [default: 1]
    -s, --sleep <sleep_period>  Sleep period in minutes [default: 1]
```
