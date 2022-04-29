# rust-listener
Simple port listener wrtitten in rust. It is used for gathering PRNG data into log file, which can be utilized by Dieharder framework. It takes 2 arguments: port name and baud rate. Example run command:
```
cargo run COM8 460800
```

The listener itself requires "log.txt" to run. There is log_ref.txt file provided with specific header parsed by Dieharder framework.
